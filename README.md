# 3D_Object_Detection
Objects detection in 3D point clouds given by measurements from LiDAR and camera from the Waymo Open Dataset

In this write-up we analyze several examples of vehicles appearing in the point cloud returned by LiDAR sensor onboard the Waymo vehicle. 

general_point_cloud

<p align = "center">
  <img src = "https://user-images.githubusercontent.com/74416077/185808403-6d3488d1-38ea-4c12-bce2-b629f9e29476.png" width=200 ></p><p align = "center">
img #1
</p>
img #1 includes several cars positioned behind the ego vehicle: for this reason we can see a detailed front part with decreasing precision in their representation when increasing the distance.

<p align = "center">
  <img src = "https://user-images.githubusercontent.com/74416077/185808463-0822ae74-96c1-4b7b-bf3f-a6d94d1cef94.png" width=200 ></p><p align = "center">
img #2
</p>
In 2 mirrors are visible although the low level of visibility given the far position of the object.

<p align = "center">
  <img src = "https://user-images.githubusercontent.com/74416077/185808577-c23afce6-c9d7-4718-92e5-7afe5508d13a.png" width=200 ></p><p align = "center">
img #3
</p>
In 3 these cars are located on the left side of the ego vehicle but really close to it, so they are easily distinguishable. 

<p align = "center">
  <img src = "https://user-images.githubusercontent.com/74416077/185808636-79f3a0d6-2f27-4f93-ab00-5ffd76c5239e.png" width=200 ><img src = "https://user-images.githubusercontent.com/74416077/185808659-14d8656f-2b31-4a7f-b5ab-a7d0a3254cd4.png" width=200 ></p><p align = "center">
img #4 and #5
</p>
#4 and #5 represent vehicles perceived on the background, main features are appreciable also in this case.

<p align = "center">
  <img src = "https://user-images.githubusercontent.com/74416077/185808703-1ea278ca-b69f-40dd-aed0-056a6294fa7f.png" width=200 ></p><p align = "center">
img #6
</p>
In 6 we can see several vehicles parked on the side of the road. Again, being very close to the sensor, all their feature are perceived and accurately represented in the point cloud.  

<p align = "center">
  <img src = "https://user-images.githubusercontent.com/74416077/185808721-db667d98-1b93-4abe-97ba-b40f8465b15b.png" width=200 ></p><p align = "center">
img #7
</p>
#7 enclose a very detailed representation of vehicles that follow the Waymo one in traffic. 

In 13 we have cars that preceed the ego vehicle, also at a great distance, cases in which visibility degrades significantly  

In 14 another distant car is seen sideways but still recognizable

In 16 a heavy-duty vehicle can be seen in the background, characterized by its rear bumper and wheels.

Main recurring features: windshields and windows (e.g. img #2, #3, #7, #14), mirrors (e.g. #2, #7), wheels (e.g. #3, #4, #14, #16 ), bumpers (e.g. #6, #16)
