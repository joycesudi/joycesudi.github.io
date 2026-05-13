---
title: "Quadcopter Testbed"
collection: portfolio
permalink: /portfolio/quadcopter-testbed/
excerpt: "Design and Development of a Quadcopter Testbed (Master's Thesis)"
teaser: /images/teaser/banc_de_test.jpg
layout: single
share: false
related: false

buttons:
  - text: "Thesis"
    url: "/files/quadcopter/quadcopter_project_report.pdf"
    color: "green"
    external: true
    
  - text: "Slides"
    url: "/files/quadcopter/quadcopter_project_slides_presentation.pdf"
    color: "green"
    external: true

  - text: "Blueprint"
    url: "/files/quadcopter/blueprint_testbed.pdf"
    color: "green"
    external: true

highlights:
  - "Quadcopter Flight Dynamics"
  - "MATLAB/Simulink"
  - "PID Attitude Control"
  - "Arduino Embedded Control"
---
<p class="about-intro">
At Ampère Laboratory – CNRS UMR 5005, I developed a quadcopter testbed intended to support practical teaching in flight dynamics and aerospace systems control. 
The project covered the full workflow from flight dynamics modeling and MATLAB/Simulink simulation to the design, assembly, and testing of a real quadcopter prototype and a 4-degree-of-freedom test bench. I designed and tuned a PID-based attitude controller for the Simulink model and its implementation on the prototype using Arduino hardware, IMU sensing, ESC-driven BLDC motors, and real-time experimental validation.
</p>

![Predictive path-tracking project image](/images/banc_de_test.jpg)

{% include project-highlights.html highlights=page.highlights %}

{% include project-buttons.html buttons=page.buttons %}
