---
title:  Warehouse Manipulator Robot Controller
tags:
  - Mechatronics
  - MATLAB
  - Simulink
  - Control
  - Feedback Linearisation
  - Modelling
images:
  - \theme\img\images\warehouse-manipulator\introImage.PNG
  - \theme\img\images\warehouse-manipulator\wholeModel.PNG
  - \theme\img\images\warehouse-manipulator\giphy.gif
  
---
<div class="card mb-3">
    <img class="img-thumbnail" src="\theme\img\images\warehouse-manipulator\introImage.PNG"/>
    <div class="card-body bg-light">
    </div>
</div>

<!--more-->

As a part of a semester assignment for a mechatronics course at UCT, was required to go through a design process for the simulation of a warehouse package handler robot.

This process consisted primarily of three stages
1. Modelling: This consisted of characterising the system given the specification restraints and getting the relevant equations of motion for the robot.
2. Controller Design: this consisted of the design of a feedback-linearisation based, State-space designed controller which was able to direct the end affector of the robot to the commanded position.
3. State estimation and advanced control: This stage consisted of designing the controller such that the manipulator was able to pick up a (simulated) package of unknown mass, estimate its mass then be manipulate this box to a commanded position. 

This whole project was carried out using MATLAB and simulink and was a simulated system only. Images of the simulink models are shown below

The final stages of this project required a substantial amount of problem solving with regards to gain sheduling and design of a robust controller. I thoroughly enjoyed this stage of the process. 

I thoroughly enjoyed this project and enjoyed going through the full process of system identification, design and simulation. The only change I would have made to this project is I would have liked to be able to test out my controller on a physical system. If you are interested you can find my report summarising this project [here]({{ site.baseurl}}{% link docs/WHTDYL001_EEE4119_Project_Report.pdf %}) 

<div id="carouselExampleControls" class="carousel slide mb-4" data-ride="carousel">
    <div class="carousel-inner">
        {% for img in page.images %}
            <div class="carousel-item {% if forloop.first %}active{% endif %}">
                <img src="{{ img }}" class="d-block w-100" alt="">
            </div>
        {% endfor %}
    </div>
    <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="False"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>