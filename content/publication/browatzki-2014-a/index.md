---
title: Active in-hand object recognition on a humanoid robot
authors:
- Bjorn Browatzki
- Vadim Tikhanoff
- Giorgio Metta
- Heinrich H. Bulthoff
- Christian Wallraven
date: '2014-01-01'
publishDate: '2024-01-04T20:45:04.100062Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Robotics*'
doi: 10.1109/TRO.2014.2328779
abstract: For any robot, the ability to recognize and manipulate unknown objects is
  crucial to successfully work in natural environments. Object recognition and categorization
  is a very challenging problem, as 3-D objects often give rise to ambiguous, 2-D
  views. Here, we present a perception-driven exploration and recognition scheme for
  in-hand object recognition implemented on the iCub humanoid robot. In this setup,
  the robot actively seeks out object views to optimize the exploration sequence.
  This is achieved by regarding the object recognition problem as a localization problem.
  We search for the most likely viewpoint position on the viewsphere of all objects.
  This problem can be solved efficiently using a particle filter that fuses visual
  cues with associated motor actions. Based on the state of the filter, we can predict
  the next best viewpoint after each recognition step by searching for the action
  that leads to the highest expected information gain. We conduct extensive evaluations
  of the proposed system in simulation as well as on the actual robot and show the
  benefit of perception-driven exploration over passive, vision-only processes at
  discriminating between highly similar objects. We demonstrate that objects are recognized
  faster and at the same time with a higher accuracy.
---
