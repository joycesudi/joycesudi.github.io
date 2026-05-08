---
title: "Digital Twin for Load Identification"
collection: portfolio
permalink: /portfolio/digital-twin-for-load-identification/
excerpt: "3D Vehicle Digital Twin for Load Identification Using Real Driving Data"
teaser: /images/train_arrière.PNG
layout: single
share: false
related: false

buttons:
  - text: "Diagram"
    url: "/files/Vehicule_Class_Diagram.jpg"
    color: "green"
    external: false

  - text: "Code"
    url: "https://github.com/joycesudi/quaternion"
    color: "gray"
    external: true

highlights:
  - "Internship"
  - "Digital Twin"
  - "Multibody Vehicle Modeling"
  - "Extended Kalman Filter"
---
<p class="about-intro">
During my internship at Stellantis, I worked on the integration of a 3D vehicle digital twin for load identification and data fusion from real driving measurements. The project focused on the automated generation of a rigid multibody vehicle model in Python and its coupling with a constrained augmented Extended Kalman Filter to reconstruct loads, dynamic states, and physical parameters that are difficult to measure directly. This work aimed to support suspension and chassis design by improving knowledge of the vehicle’s dynamic state while reducing reliance on costly instrumentation through model-based estimation and reusable engineering tools.
</p>

![Digital Twin for Load Identification](/images/train_arrière.PNG)

{% include project-highlights.html highlights=page.highlights %}

{% include project-buttons.html buttons=page.buttons %}
