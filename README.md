# Practical_Robotic_Grasping_Method

## Prepare
### ROS packages
>> 1. realsense2_camera
>> 2. DOPE: git clone: https://github.com/NVlabs/Deep_Object_Pose.git

### Environments
>> 1. Python2.7
>> 2. torch==1.4.0

## Run
> 1.$ roslaunch realsense2_camera rs_camera.launch
> 2.$ rosrun dope dope.py
> 3.$ rqt_image_view
> 4.PS: rostopic: rgb_dope_points
