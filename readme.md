# YDLidar ROS 2.0 Wrapper   
This is ROS version pkg based on original EAI-ydlidar ros wrapper repo.  

## Developers  
* Alan, Chen (alan.chen@adlinktech.com)  
* HaoChih, LIN (haochih.lin@adlinktech.com)  

## License  
Apache 2.0 (Copyright 2018 ADLINK Technology, Inc.)  
  
## Compile (examples)      
$ cd ~/ros2_ws  
$ ament build  
OR (build only)  
$ ament build --only-packages ydlidar  

For isolated build  
$ ament build --isolated --build-tests --symlink-install --only ydlidar  

## Execute
$ ros2 run ydlidar ydlidar_node  
