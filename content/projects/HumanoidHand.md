---
title: "Humanoid Soft-Robotic Hand"
date: 2024-06-01
draft: false
description: "3D printed robotic end-effector for a humanoid robot for the Melbourne Space Program"
tags:
  - 3D printing
  - CAD models
  - Soft Robotics
image: "/images/MSP/MSP_hand_gif_hz.gif"
featured: true
---

Single motor design connected via internal strings to each finger. Actuating the motor contracts the fingers. Fingers modelled based on actual human hand, and fingers 3D printed to to exhibit human range of motion. 

#### Initial Finger Prototype vs Final Iteration 
Showcases initial finger bending test, vs final design model, with humanoid hand and fingers implemented.
<div style="display: flex; gap: 1rem; flex-wrap: wrap; justify-content: center;">

  <div style="text-align: center;">
    <iframe width="280" height="500"
      src="https://www.youtube.com/embed/iY-L_qGGkqY"
      title="YouTube Short 1"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen>
    </iframe>
    <p style="margin-top: 0.5rem;">Finger Contraction Prototype</p>
  </div>

  <div style="text-align: center;">
    <iframe width="280" height="500"
      src="https://www.youtube.com/embed/QIDXISR6dcA"
      title="YouTube Short 2"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen>
    </iframe>
    <p style="margin-top: 0.5rem;">♟️ Final Humanoid Hand End Effector</p>
  </div>

</div>

<br>
<br>

#### Object Gripping Test 

<iframe width="100%" height="450" 
  src="https://www.youtube.com/embed/SY2eah3Jmb0" 
  title="YouTube Short" 
  frameborder="0" 
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
  allowfullscreen>
</iframe>

<br>
<br>

#### Design

Made in collaboration with Melbourne Human Robotics lab:                        <a href="https://blogs.unimelb.edu.au/human-robotics/advanced-prosthetics/" target="_blank" style="color: #007bff;">https://blogs.unimelb.edu.au/human-robotics/advanced-prosthetics/</a>

Simple single motor design intended for gripping single objects.

#### Materials 
- **Motor** - DYNAMIXEL XC330-M288-T
      (<a href="https://www.robotis.us/dynamixel-xc330-m288-t/?srsltid=AfmBOooo3MVZxc8DRuWU91PAbEoB_azSS8ODdNmaCLtyu_8qW7vl4Be0" target="_blank" style="color: #007bff;">https://www.robotis.us/dynamixel-xc330-m288-t</a>)
- **Filament** - TPU 87A (Best available for flexibility / strength tradeoff)

#### 3D Printing Settings

- Disable supports 
- Mateiral TPU 87A 
- 100% solid infill (Design containts empty cavities so we need 100% infill to ensure structural integrity)
- Orient all fingers vertically standing up
- layer height but if you can, do a 0.16 or 0.2 mm layer height


#### STL file close-up
<img src="/images/MSP/MSP_humanoidHand.png" alt="MSP Humanoid Hand CAD Model" style="width:100%; max-width:700px; display:block; margin:auto;">


