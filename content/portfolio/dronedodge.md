+++
date = "2019-08-01"
weight = 110
description = "An Senior Design award winning projectile dodging solution"
title = "Projectile Evasion System for UAV"
draft = false
bref= "A UAV framework to recognize and dodge projectiles"
toc = true
+++

## The Background
As Seniors at the University of Texas at Dallas, we are required to go through a semester of "Senior Desgin" where we can collaborate with a mentor from both a local business and faculty at our school. I joined up with a team of people I had never worked with before, and we decided to pursue a projects that Raytheon had to offer. We were selected to be part of what was orignially a "cyber-security" project with Raytheon, building on what previous semesters had worked on, but we quickly realized that the work was not going to be particularly challenging for us, so we proposed an idea that I had: to try to build a drone which would use machine vision to recognize projectiles and perform evasive maneuvers.

## The Project
While I am contractually not allowed to give specifics about how we implemented the framework, I can say what my contribution was. I was primarily responsible interfacing between the lower level embedded software, the higher level flight control, and the hardware. I essentially had the fun job of the group. Some of us worked on programming the Machine Vision Cameras, and others worked on the dodging system itself. I worked to make sure everything worked together. I constructed the drone itself, and worked with the beagle-bone and raspberry pi to work implement the "Ardupilot" flight software interface
<figure>
    <img alt="4px horizontal rhythm" src="/img/drone.jpg" class = "center-image">
    <figcaption>
      <h7 class = "center-image">When the drone was finally constructed</h7>
  </figcaption>
</figure>

## The Results 
Out of a record breaking 52 teams presenting at the end of the semester, ours was awarded 2nd Place overall. We created a software package that could modularly accept new sensors to detect hazards, and worked using entirely open source hardware and software components. Furthermore, it successfully recognized the objects we trained it to recognize, and would fly under both remote-control and autopilot. We showed our results not only to the UT Dallas students and staff, but also Raytheon who sponsored the project. This was an incredibly rewarding project, and I'm happy I got to step up to a real challenge, and was rewarded for that effort.

<figure>
    <img alt="4px horizontal rhythm" src="/img/dronegroup.jpg" class = "center-image">
    <figcaption>
      <h7 class = "center-image">Second Placed Team out of 52</h7>
  </figcaption>
</figure>

## Social Media
If interested in learning further, I have posted more information on my LinkedIn
[here](https://www.linkedin.com/posts/benjaminjhill_machinevision-activity-6544268669902483456-fqux)