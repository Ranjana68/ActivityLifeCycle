# ActivityLifeCycle

To navigate transitions between stages of the activity lifecycle, the Activity class provides a core set of
basically seven callbacks:
1) onCreate()
2) onStart()
3) onPause()
4) onPostResume()
5) onStop()
6) onRestart()
7) onDestroy()

RUNNING PROCESS:
• When we have to start application, internally 3 methods are executed
1) onCreate()
2) onStart()
3) onPostResume()
• When we close with home button, internally 2 methods are executed which pauses application , as it still runs in the background
1) onPause()
2) onStop()
• When we have to restart our application, 3 methods are executed
1) onRestart()
2) onStart()
3) onPostResume()
• When closed with back button , 3 method are executed which stops the application
1) onPause()
2) onStop()
3) onDestroy()
