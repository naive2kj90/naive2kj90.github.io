---
layout: page
title: Face Clone
subtitle: Real-time High-Quality 3-D Face Tracking System
---

Page about Face Clone.

## System Design

Our proposed system is designed as a two-stage work- flow. First, the deformable high-quality 3-D face scan is made from photos taken in the camera studio. Then, when the user moves their face or talks as they want, the 3-D face scan moves as save as the user in real-time.

![Studio](/assets/img/1_system.png){:width="60%"}

Camera studio

![Flow](/assets/img/3_flow1.png){:width="60%"}

The flow of 3-D face scan generation (for the 1st frame)

![Flow](/assets/img/3_flow2.png){:width="60%"}

The flow of real-time face animation (for the 2nd and the rest frames)

### GUI Interface

Our system aims to mirror facial movement with a photo- realistic face model. We provide our system through the in- terface consisting of the image panel, the face model panel, and the animation panel, controlling from the start to the end. The general steps for the user on the interface include

![Flow](/assets/img/4_interfacea.png){:width="60%"}

Upon completion of 3-D face generation and 3-D face landmark estimation, the results are displayed to the user in the interface. The captured images and generated 3-D face remain visible until the user is satisfied with the result. Then, a scene featuring the user’s photo-realistic 3-D face, synchronized with the captured facial motion, is presented in real-time with exceptional quality by the rendering engine.

![Flow](/assets/img/4_interfaceb.png){:width="60%"}

An interactive tool for user-customized rendering. The system automatically provides the result but the user can adjust the output through the in- terface. The user can wear some pre-defined accessories to the face. We provide glasses, tattoos, and hat options.
