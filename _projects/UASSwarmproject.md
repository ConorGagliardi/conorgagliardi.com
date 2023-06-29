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


**Currently working on:**

- Implementing formation changes.
- Training a CNN / using a pre-trained YOLO network for drone recognition to replace the green ball with.
- Collision avoidance
- Collision maneuvering using formation changes.



[Github Repo](https://github.com/ConorGagliardi/Monocular-Swarm)<br>

**Physical Demo Videos, click images to open youtube link (top is most recent, more to come)**

*Momentum based prediction for monocular drone formation*

[![Demo Video](http://img.youtube.com/vi/6lF3zOCgCX8/0.jpg)](http://www.youtube.com/watch?v=6lF3zOCgCX8)

*Demo Program running, relative localization of a follower agent, using momentum based prediction*

[![Demo Video](http://img.youtube.com/vi/PvklLIARG7k/0.jpg)](http://www.youtube.com/watch?v=GC-PvklLIARG7k)

*Weighted vs unweighted momentum prediction test* 

[![Demo Video](http://img.youtube.com/vi/BsxpXkCZvg4/0.jpg)](http://www.youtube.com/watch?v=BsxpXkCZvg4)

*Momentum Test using DJI Tello Camera*

[![Demo Video](http://img.youtube.com/vi/gqzmbzOukcQ/0.jpg)](http://www.youtube.com/watch?v=gqzmbzOukcQ)


*Leader follower demo*

[![Demo Video](http://img.youtube.com/vi/2iU-LPFT6nQ/0.jpg)](http://www.youtube.com/watch?v=2iU-LPFT6nQ)



**Simulation Demo Videos, click images to open youtube link (top is most recent, more to come)**

*momentum predictor implemented*

[![Demo Video](http://img.youtube.com/vi/oH6bX-O1VLA/0.jpg)](http://www.youtube.com/watch?v=oH6bX-O1VLA)

*With threading*

[![Demo Video](http://img.youtube.com/vi/pOn2-BmXH08/0.jpg)](http://www.youtube.com/watch?v=pOn2-BmXH08)

*Without threading*

[![Demo Video](http://img.youtube.com/vi/QukUG3KtupY/0.jpg)](http://www.youtube.com/watch?v=QukUG3KtupY)

**Midterm Presentation**


<iframe src="/files/REU_Midterm.pdf" width="100%" height="800" frameborder="no" border="0" marginwidth="0" marginheight="0"></iframe>
