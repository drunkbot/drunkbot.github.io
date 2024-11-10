---
layout: page
title: Digital twin platform for cyber–physical robot fleets
description: SARESE x RNE Research Sprint 2022.
img: assets/img/1N3A6565.JPG
importance: 3
category: work
related_publications: true
---

<h2>Overview</h2>
Development of mixed multi-robot fleet utilising a cyber-physical systems architecture in dynamic inspection, maintenance and repair missions. My role is to develop Tello Drone software for pre-inspecting simulated radioactive arenas, coordinating with multi-robot fleets, and interacting with a cyber system via ROS.

<h2>Collaborators</h2>
University of Glasgow, Bristol Robotics Laboratory, Sellafield Ltd, RAICo1 Lab

<p>Outcome</p>
Created a mixed multi-robot fleet utilising a cyber-physical systems architecture in dynamic inspection, maintenance and repair missions.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    <div class="embed-responsive embed-responsive-16by9">
      {% include video.liquid path="https://www.youtube.com/embed/0EJ8Y8esQz0?si=kUeAilzkaYl_fio9" class="embed-responsive-item rounded z-depth-1" %}
    </div>
  </div>
</div>
<div class="caption">
  {% cite Baniqued2024 %}
</div>

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    <div class="embed-responsive embed-responsive-16by9">
      {% include video.liquid path="https://www.youtube.com/embed/Tz_PNtG5CGE?si=zoj3DczYvm_kmCKz" class="embed-responsive-item rounded z-depth-1" %}
    </div>
  </div>
</div>
<div class="caption">
{% cite Mitchell2023 %}
</div>

<h3>Subsection 1.1</h3>

<p>Content of subsection 1.1.</p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
