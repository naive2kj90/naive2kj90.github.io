---
layout: page
title: Face Clone
subtitle: Real-time High-Quality 3-D Face Tracking System
---

The main goal of our experiment is to show a real-time detailed 3-D face tracking system. The face tracking system consists of two big steps to consider. First, we have to make a deformable 3-D face scan. The quality of the face depends on what purpose the user wants to use it. Second, we have to track the face and deform the 3-D face scan from 1th step. The 3-D face, shown on the screen has to track the user’s face and deform in a few milliseconds to provide a real-time experience.
{: .text-justify}


## System Design

Our proposed system is designed as a two-stage workflow. First, the deformable high-quality 3-D face scan is made from photos taken in the camera studio. Then, when the user moves their face or talks as they want, the 3-D face scan moves as save as the user in real-time.
{: .text-justify}

![Studio](/assets/img/1_system.png){:width="400px"}

Camera studio
{: .text-justify}

![Flow](/assets/img/3_flow1.png){:width="400px"}

The flow of deformable 3-D face scan generation (for the 1st frame)
{: .text-justify}

![Flow](/assets/img/3_flow2.png){:width="400px"}

The flow of real-time face animation (for the 2nd and the rest frames)
{: .text-justify}


### GUI Interface

Our system aims to mirror facial movement with a photo- realistic face model. We provide our system through the in- terface consisting of the image panel, the face model panel, and the animation panel, controlling from the start to the end.
{: .text-justify}

![Flow](/assets/img/4_interfacea.png){:width="400px"}

Upon completion of 3-D face generation and 3-D face landmark estimation, the results are displayed to the user in the interface. The captured images and generated 3-D face remain visible until the user is satisfied with the result. Then, a scene featuring the user’s photo-realistic 3-D face, synchronized with the captured facial motion, is presented in real-time with exceptional quality by the rendering engine.
{: .text-justify}

![Flow](/assets/img/4_interfaceb.png){:width="400px"}

An interactive tool for user-customized rendering. The system automatically provides the result but the user can adjust the output through the in- terface. The user can wear some pre-defined accessories to the face. We provide glasses, tattoos, and hat options.
{: .text-justify}


### Result

Demo video on 3-D face deformation.
{: .text-justify}

<iframe
        width="100%" height="315" src="https://www.youtube.com/embed/aaCEkpZXNpA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen>
</iframe>

Demo video (temp)
{: .text-justify}
