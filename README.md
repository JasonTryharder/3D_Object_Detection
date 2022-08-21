# 3D_Object_Detection
Objects detection in 3D point clouds given by measurements from LiDAR and camera from the Waymo Open Dataset

In this write-up we analise several examples of vehicles appearing in the point cloud returned by LiDAR sensor onboard the Waymo vehicle. 

general_point_cloud

1 include several cars positioned behind the ego vehicle: for this reason we can see a detailed front part with decreasing precision in their representation when increasing the distance.

In 6 these cars are located on the left side of the ego vehicle but really close to it, so they are easily distinguishable. 

8 and 9 represent vehicles perceived on background, main features are clearly appreciable also in this case.

In 10 we can see several vehicles parked on the side of the road. Again, being very close to the sensor, all their feature are perceived and accurately represented in the point cloud.  

11 enclose very detailed representation of vehicles that follow the Waymo one in the traffic. 

In 13 we have cars that preceed the ego vehicle, also at a great distance, case in which visibility degrades significantly  

Main recurring features are: windshields and windows, mirrors, wheels 