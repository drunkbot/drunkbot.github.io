---
layout: page
title: Patrol and Priority Control
description: Development of autonomous patrolling and priority control algorithm. Robots navigate with <strong>TEB planner</strong> and <strong>RSNP server</strong>, object detection achieved by <strong>YOLO</strong>, robots communicate with each other via <strong>MQTT protocol</strong>. 
img: assets/img/utokyo_cover.png
importance: 5
---


<h2>Overview</h2>
Development on autonomous patrolling and priority control.

Developed a priority control algorithm that allows multiple robots cooperatively navigate narrow paths, addressing a critical limitation of the previous system.

<h2>Collaborators</h2>
Dr Nobuto Matsuhira from the University of Tokyo, and Young-woon Song from Pohang University of Science and Technology.

<div class="row justify-content-sm-center">
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/utokyo_1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/utokyo_cover.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left shows the diagram of autonomous patrolling and on the right shows the narrow path that two robots got stuck.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/patrolling.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=false %}
    </div>
</div>
<div class="caption">
    Autonomous patrolling
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/priority_control.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=false %}
    </div>
</div>
<div class="caption">
    Priority control
</div>