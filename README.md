# 3D_Object_Detection
Objects detection in 3D point clouds given by measurements from LiDAR and camera from the Waymo Open Dataset

In this write-up we analyze several examples of vehicles appearing in the point cloud returned by LiDAR sensor onboard the Waymo vehicle. 

general_point_cloud

<p align = "center">
  <img src = "https://user-images.githubusercontent.com/74416077/185808403-6d3488d1-38ea-4c12-bce2-b629f9e29476.png" width=200 ></p><p align = "center">
img #1
</p>

<!--<img src="https://user-images.githubusercontent.com/74416077/185808403-6d3488d1-38ea-4c12-bce2-b629f9e29476.png" width=200 alt=/>-->

img #1 includes several cars positioned behind the ego vehicle: for this reason we can see a detailed front part with decreasing precision in their representation when increasing the distance.

<img src="https://user-images.githubusercontent.com/74416077/185808463-0822ae74-96c1-4b7b-bf3f-a6d94d1cef94.png" width=200 alt="img #1"/>
In 3 mirrors are visible although the low level of visibility given the far position of the object.

In 6 these cars are located on the left side of the ego vehicle but really close to it, so they are easily distinguishable. 

8 and 9 represent vehicles perceived on the background, main features are appreciable also in this case.

In 10 we can see several vehicles parked on the side of the road. Again, being very close to the sensor, all their feature are perceived and accurately represented in the point cloud.  

11 enclose a very detailed representation of vehicles that follow the Waymo one in traffic. 

In 13 we have cars that preceed the ego vehicle, also at a great distance, cases in which visibility degrades significantly  

In 14 another distant car is seen sideways but still recognizable

In 16 a heavy-duty vehicle can be seen in the background, characterized by its rear bumper and wheels.

Main recurring features: windshields and windows (e.g. img #3, #6, #11, #14), mirrors (e.g. #3, #11), wheels (e.g. #6, #8, #14, #16 ), bumpers (e.g. #10, #16)
