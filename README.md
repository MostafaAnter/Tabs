# Working with tabs
frist thing you should know to work with tabs is Fragment 

# Creating a Fragment
To create a fragment, you must create a subclass of Fragment (or an existing subclass of it). The Fragment class has code that looks a lot like an Activity. It contains callback methods similar to an activity, such as onCreate(), onStart(), onPause(), and onStop(). In fact, if you're converting an existing Android application to use fragments, you might simply move code from your activity's callback methods into the respective callback methods of your fragment.
[example of how two UI modules defined by fragments can be combined into one activity for a tablet design, but separated for a handset design.](http://developer.android.com/images/fundamentals/fragments.png)
