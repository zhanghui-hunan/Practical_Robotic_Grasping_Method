# Practical_Robotic_Grasping_Method

## Prepare
### ROS packages
>> 1. realsense2_camera
>> 2. ROOT: git clone: https://github.com/zhanghui-hunan/Practical_Robotic_Grasping_Method.git

### Environments
>> 1. Python2.7
>> 2. torch==1.4.0

### Download weight
>> <br> Download from Baidu Pan: 链接：https://pan.baidu.com/s/11FfmY-IfbzYLuMu8qAsJGA , Extract the code：u0sj 

## Run
<br> > $ roslaunch realsense2_camera rs_camera.launch
<br> > $ rosrun Practical_Robotic_Grasping_Method dope.py
<br> > $ rqt_image_view
<br> > PS: rostopic: rgb_dope_points
