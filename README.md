# sylu_rader2023

编译环境：

ubuntu18.04 , ros,pcl1.9.1,eigen3.3.4,opencv3.4.16,MVS,livox-SDK,qt5

开启命令：

终端一：

source devel/setup.bash

roslaunch leida1 robot_lidar.launch

终端二：

source devel/setup.bash

conda activate yolo   

rosrun yolov5_7 final_yolo.py

注：yolo为yolov5-6.1环境。
