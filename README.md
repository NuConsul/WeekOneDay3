# WeekOneDay3

1. The major components of Android are also explained in a design known as the software stack. 
This includes (from the bottom up) the Power Management System, the Linux Kernel [with its drivers], 
the Hardware Abstraction Layer, Native C/C++ Libraries, Android Runtime, the Java API Framework, and the Systems Apps.

2. The activity lifecycles are the onCreate() method, onStart() method, onResume() method, 
onPause() method, onStop() method, onRestart() method, and the onDestroy() method. 
The onCreate method is the first method to be called associated with a activity. 
This details initializing any UI views, etc. The onStart() method is called after the onCreate() method 
and makes the activity visible to the user. Next is the onResume() method which is called when the Activity 
is in the foreground. Once the activity is in the onResume() state the next method that can be called is the 
onPause() method if the activity is no longer in the foreground. If the activity is no longer visible to the 
user it will then call the onStop() method. This method is where you can unregister things such as listeners. 
If the activity goes from being no longer visible to the user to visible the onRestart() method will be called. 
In this method you can do things like re-registering listeners. The last method to which can be called on an 
activity is the onDestroy() method. This method will be called right before the activity is destroyed. 
It is typically used to handle any final instructions to be done with the activity that was not handled by 
say the onStop() method. 

3. The sprint agile method begins with a sprint planning session on Monday typically. 
The developers will do a stand up explaining things like what was done before. 
What is being worked on that day, any issues, etc. The process will repeat itself throughout the week. 
That Friday the grooming session will commence, which typically entails the developer and/or designer 
explaining if the new feature works or not. The following week the typical daily standups continue. 
Usually on that Wednesday the developer does a pull request for the new feature. 
On that Thursday the feature that has been done is demoed or displayed. 
Then that Friday the Pull Request can be approved and rolled out for the application software. 

4. Davlik is a discontinued Virtual Machine in Android’s operating system that 
executed applications written for Android. Android Runtime is an application runtime 
environment used by the Android operating system. 

5. It is layered.
