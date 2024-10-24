---
layout: page
title: Robot Simulator
description: a software tool for simulating robots
img: /assets/img/robotSimulator.PNG
importance: 1
category: work
related_publications: false
---

I independently developed a motion simulator for robotic systems that aid in detecting collisions and visualizing movements. By combining a left-child, right-sibling tree data structure with the Denavit-Hartenberg (DH) convention, I utilized a preorder traversal algorithm to efficiently draw and display complex assemblies. I also invented the Single-Axis Dragging algorithm, enabling users to control the joint-space motion of a six-axis robotic arm with simple click-and-drag interactions. Additionally, I created a patented 6 Degrees of Freedom (DoF) interactive marker and algorithm, allowing intuitive manipulation of a robot's end-effector position and orientation. To solve the Inverse Kinematics problem, I implemented the Damped Least Squares method for numerical optimization.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/robotSimulator.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    A demostration of the software's features.
</div>

**Keywords**: Industrial Robot, CAD modelling, Animation, Kinematics, Damped Least Squares, Collision Detection, OpenGL, Bullet Physics, C#.