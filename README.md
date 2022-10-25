# 3dlidar_ws

Installation

```
sudo apt-get install ros-melodic-geodesy ros-melodic-pcl-ros ros-melodic-nmea-msgs ros-melodic-libg2o

sudo apt-get install ros-melodic-velodyne

mkdir 3dlidar_ws/src

cd 3lidar/src

git clone https://github.com/GPMxYunTech/3dlidar_ws.git

cd ..



catkin_make -DCATKIN_WHITELIST_PACKAGES="velodyne"

catkin_make -DCATKIN_WHITELIST_PACKAGES=""
```

