![alt text](https://github.com/Hypha-ROS/hypharos_minibot/blob/master/document/logo/HyphaROS_logo_2.png)  
![alt text](https://github.com/Hypha-ROS/hypharos_minibot/blob/master/document/HyphaROS_MiniBot_photo.jpg)  

## Abstract
This is a sample code for final projects using HyphaROS Minibot.   
This code activate a node "main" and the other sensor nodes. 
Main node subscribes three topics -- imu_data, odom, and scan. 
You can access data from three Callback functions.


## About us
Contact: kuoshih@math.ncu.edu.tw
Developer:   
* Kuo-Shih Tseng

Date: 2018/10/22  
License: Apache 2.0  


##Compile the code
$ cd catkin_ws/src  
$ git clone https://github.com/kuoshih/hypharos_minibot   
$ cd ..  
$ catkin_make  

Or Download this this code to pi\catkin_ws\src.   
Unzip hypharos_minibot.zip to replace the original code.
  
$cd catkin_ws  
$catkin_make  

##Run the code   
$roslaunch hypharos_minibot project_sample.launch

More information about Minibot can be found https://github.com/Hypha-ROS/hypharos_minibot.   
