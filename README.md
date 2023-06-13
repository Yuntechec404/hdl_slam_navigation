# 3D-LiDAR Project Installation
```
sudo apt-get install ros-noetic-velodyne ros-noetic-geodesy ros-noetic-pcl-ros ros-noetic-nmea-msgs ros-noetic-libg2o

mkdir -p ~/3dlidar_ws/src 

cd ~/3dlidar_ws/src

git clone https://github.com/GPMxYunTech/3dlidar_ws.git

cd ..

rosdep install --from-paths src --ignore-src -r -y

catkin_make --pkg velodyne

catkin_make 

echo "source ~/3dlidar_ws/devel/setup.bash" >> ~/.bashrc

source ~/.bashrc
```

# 3D-LiDAR Setting
Set IP

| Identity Name     | IP Address    | Netmask         |
| --------          | --------      | --------        |
| 3D-LiDAR_VLP16    | 192.168.1.70  | 255.255.255.0   |

![](https://i.imgur.com/6Nyy9A6.png)
