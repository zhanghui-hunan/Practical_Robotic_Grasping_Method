# Practical_Robotic_Grasping_Method

## Prepare
### ROS packages
>> 1. realsense2_camera
>> 2. DOPE: git clone: https://github.com/NVlabs/Deep_Object_Pose.git

### Environments
>> 1. Python2.7
>> 2. torch==1.4.0

## Run
<br> > $ roslaunch realsense2_camera rs_camera.launch
<br> > $ rosrun dope dope.py
<br> > $ rqt_image_view
<br> > PS: rostopic: rgb_dope_points
