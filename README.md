
Hello EveryOne,
  To use this "customTabsWithViewPager" code into your existing project you need to follow some steps.
    1. Add this library into module level app
          compile 'com.android.support:design:25.3.1'
    2. Add tab layout into yyour design where you want tabs 
    3. Initialize View pager adapter and then add fragments into it then set this adapter to view pager.
    4. pass the view pager to tablayout by calling setupWithViewPager().
  
  Now you are good to go. :-)
