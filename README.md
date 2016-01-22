# Working with tabs
frist thing you should know to work with tabs is Fragment 

# Creating a Fragment
To create a fragment, you must create a subclass of Fragment (or an existing subclass of it). The Fragment class has code that looks a lot like an Activity. It contains callback methods similar to an activity, such as onCreate(), onStart(), onPause(), and onStop(). In fact, if you're converting an existing Android application to use fragments, you might simply move code from your activity's callback methods into the respective callback methods of your fragment.
![alt tag](http://developer.android.com/images/fundamentals/fragments.png)

# steps
this steps just simple hint to use this project inside your project just follow steps and navigate project

- Under your main package create a fragment named OneFragment.java
- create a fragment_one.xml located under res ⇒ layout
- Likewise create few more fragment activities with same code we used for OneFragment.java. I have created TwoFragment.java, ThreeFragment.java
- Open the layout file of main activity (activity_main.xml) and add Tab attributs 
- Open MainActivity.java and do some changes changes.

# ScreenShot
![alt tag](https://github.com/MostafaAnter/Tabs/blob/master/device-2016-01-22-220910.png)
