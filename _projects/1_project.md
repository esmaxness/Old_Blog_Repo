---
layout: page
title: TERMINET
description: nexT gEneRation sMart INterconnectEd ioT 
img: assets/img/TERMINET2.png
importance: 1
category: work
related_publications: Sarabia_J_come_2023
---

DESCRIPTION

The vision of TERMINET is to provide a novel next generation reference architecture based on cutting-edge technologies such as SDN, multiple-access edge computing, and virtualisation for next generation IoT, while introducing new, intelligent IoT devices for low-latency, market-oriented use cases. i2CAT will focus on the development, integration, and deployment of a RINA based IoT solution to support the requirements of intelligent IoT devices and to provide low latency.

TERMINET’s primary intention is to bring (more efficient and accurate) decisions to the point of interest to better serve the final user targeting at applying distributed AI at the edge by using accelerated hardware and sophisticated software to support local AI model training using federated learning. TERMINET solution aspires to reduce the complexity of the connecting vast number of heterogeneous devices through a flexible SDN-enabled middleware layer. i2CAT will integrate the RINA based IoT solution with SDN-enabled middleware layer to facilitate the adoption of RINA advances into IoT applications. It also aims to design, develop, and integrate novel, intelligent IoT devices such as smart glasses, haptic devices, energy harvesting modules, smart animal monitoring collars, AR/VR environments, and autonomous drones, to support new market-oriented use cases. 

ESTIMATED IMPACT

Great expectation of the proposal is to foster AR/VR contextual computing by demonstrating applicable results in realistic use cases by using cutting-edge IoT-enabled AR/VR applications. By designing and implementing an IoT-driven decentralised and distributed blockchain framework within manufacturing, TERMINET aims to support maintenance and supply chain optimisation. TERMINET intends to apply a vertical security by design methodology by meeting the privacy-preserving and trust requirements of the NG-IoT architecture. For the evaluation of its wide applicability, TERMINET will validate and demonstrate six proof-of-concept, realistic use cases in compelling IoT domains such as the energy, smart buildings, smart farming, healthcare, and manufacturing.

CORDIS link: https://cordis.europa.eu/project/id/957406



Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
