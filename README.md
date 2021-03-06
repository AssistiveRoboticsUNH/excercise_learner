The code is based on Christopher Munroe's code https://github.com/idkm23/exercise_learner with some modifications made in summer 2016.

Setup
====
To further develop this repository, one must have:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Android Jellybean (API 15, because the ODG uses this version at the time this was written 5/4/2016)   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Android Studio  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- ros indigo  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- rosjava http://wiki.ros.org/rosjava/Tutorials/indigo/Source%20Installation  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- ros android http://wiki.ros.org/android/Tutorials/indigo/Installation%20-%20ROS%20Development%20Environment 
  
Clone this repository in the src folder of a catkin_workspace:  
```
git clone https://github.com/ylmeng/exercise_learner  
cd ..  
catkin_make
```  

Then, open the exercise_learner folder in Android Studio and you should be ready to go. After you finish modifying the code, Android Studio can install the program on your Android device, if you connect it to your computer with a USB calble. You must enable installation from "Unknown Sources" in the Security setting.
  
Downloadable APK (8/16/2016)  
https://drive.google.com/file/d/0BxhtAJAynX3eSlJRcFhhZlhuN00/view?usp=sharing
  
To install via the link above, you must enable installation from "Unknown Sources" in the Security tab of the phone.
 Then you can simply click the link, download the app, and open the APK to install on any Android device.
 
Run the app
===
Before running the app, make sure your Android device is connected to the same network service as your computer. Some wifi service blocks certain ports and it may fail. I tested it at home (comcast) and it works. The eduroam on campus does not support it though. It is safer to use our own router.

- Launch an exercise interface first. Please refer to https://github.com/ylmeng/exercise_interface_client
- On your Android device, click the icon "Exercise Learner".
- If it prompts for IP address, type in the correct one. The port should be 11311.
- Then you should be able to see a 3D model. 
- You need to restart the program if you restart your exercise interface from the computer.
