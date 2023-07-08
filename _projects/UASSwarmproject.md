---
title: "Vision-Based Control of Unmanned Aerial Systems Swarm (NSF-REU)"
collection: projects
permalink: /projects/UASSwarmproject
---

**Completed**
- Quadrotor manual control in simulation
- Modifying 3D model to fit needs for task
- Green blob/ball bit mask using OpenCV
- Find edges of object to calculate radius and centroid
- Threshold boundaries for object tracking with movement policies for following
- Relative localization using radius size to maintain a consistent distance
- Multi-agent proof of concept by manipulating threshold boundaries instead of symmetrical by default (move the center square and change its size)
- Threading in simulation for better performance
- Created a movement prediction model which uses a calculated 'momentum' using a history of center points
- Implementing multithreaded solutions for more snappy visual feedback for dji tello implementation
- Formation Change in Simulation
- Trained Drone detection YOLOv8 model on 16,000 drone pictures, and fine-tuned on hundreds of DJI Tello Drones at angles likely for a follower to see [Dataset1](https://universe.roboflow.com/get/uav-detect-pfiqs/dataset/1) [Dataset2](https://universe.roboflow.com/project-tiamr/drone-detection-04s7b/dataset/13)<br>
- Implemented new 3D model that is easier to be recognized by Drone Detection Model
- Implemented tracking based on detected drone in Microsoft Airsim. Uses [BoT-SORT](https://github.com/NirAharon/BoT-SORT)<br>


**Currently working on:**
- Refining formation change for physical demo
- Training a CNN / using a pre-trained YOLO network for drone recognition to replace the green ball with
- Rotation Tracking
- Collision avoidance
- Autonomous Collision maneuvering using formation changes



Here is the [Github Repo](https://github.com/ConorGagliardi/Monocular-Swarm) for this project!



**Before and After Fine-Tuning YOLOv8 Model**
<div style="max-width: 50%; float: left;">
  <img src="/files/before%20after%20fine-tuning.PNG" style="width: 100%; height: auto; border: none; margin: 0; padding: 0;">
</div>

<br clear="both">

**Most Recent Update**

*Drone Following using YOLOv8 Microsoft Airsim Demo*

[![Demo Video](http://img.youtube.com/vi/82dp1T0wxLs/0.jpg)](http://www.youtube.com/watch?v=82dp1T0wxLs)

**Physical Demo Videos, click images to open youtube link (top is most recent, more to come)**

*Momentum based prediction for monocular drone formation*

[![Demo Video](http://img.youtube.com/vi/6lF3zOCgCX8/0.jpg)](http://www.youtube.com/watch?v=6lF3zOCgCX8)


*Demo Program running, relative localization of a follower agent, using momentum based prediction*

[![Demo Video](http://img.youtube.com/vi/PvklLIARG7k/0.jpg)](http://www.youtube.com/watch?v=PvklLIARG7k)


**Simulation Demo Videos, click images to open youtube link (top is most recent, more to come)**


*Formation Change to Maneuver Swarm Through a Narrow Cooridor*

[![Demo Video](http://img.youtube.com/vi/fH7wXxbZxAY/0.jpg)](http://www.youtube.com/watch?v=fH7wXxbZxAY)

*momentum predictor implemented*

[![Demo Video](http://img.youtube.com/vi/oH6bX-O1VLA/0.jpg)](http://www.youtube.com/watch?v=oH6bX-O1VLA)


**Early Videos (Archive)**

*Weighted vs unweighted momentum prediction test* 

[![Demo Video](http://img.youtube.com/vi/BsxpXkCZvg4/0.jpg)](http://www.youtube.com/watch?v=BsxpXkCZvg4)

*Momentum Test using DJI Tello Camera*

[![Demo Video](http://img.youtube.com/vi/gqzmbzOukcQ/0.jpg)](http://www.youtube.com/watch?v=gqzmbzOukcQ)


*Leader follower demo*

[![Demo Video](http://img.youtube.com/vi/2iU-LPFT6nQ/0.jpg)](http://www.youtube.com/watch?v=2iU-LPFT6nQ)


*With threading*

[![Demo Video](http://img.youtube.com/vi/pOn2-BmXH08/0.jpg)](http://www.youtube.com/watch?v=pOn2-BmXH08)

*Without threading*

[![Demo Video](http://img.youtube.com/vi/QukUG3KtupY/0.jpg)](http://www.youtube.com/watch?v=QukUG3KtupY)


