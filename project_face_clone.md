---
layout: page
title: Face Clone
subtitle: Real-time High-Quality Face Tracking System
---

The main goal of our experiment is to show a real-time detailed 3-D face tracking system. The face tracking system consists of two big steps to consider.
First, we have to make a deformable 3-D face scan from the 1st frame. Second, we have to track the face and deform the 3-D face scan for the 2nd and the rest frame. The 3-D face, shown on the screen has to track the user’s face and deform in a few milliseconds to provide a real-time experience.
{: .text-justify}

## System Design

Our proposed system is designed as a two-stage workflow. First, the deformable high-quality 3-D face scan is made from photos taken in the camera studio. Then, when the user moves their face or talks as they want, the 3-D face scan moves as save as the user in real-time.
{: .text-justify}

![Studio](/assets/img/1_studio.jpg){:width="400px"}

Camera studio
{: .text-justify}

![Flow](/assets/img/3_flow.png){:width="400px"}

The flow of deformable 3-D face scan generation (for the 1st frame) and the flow of real-time face tracking (for the 2nd and the rest frames)
{: .text-justify}


### GUI Interface

![Flow](/assets/img/4_interface.png){:width="400px"}

We provide our system through the interface, controlling it from the start to the end. The user can show their cloned 3-D face moving on the interface.
{: .text-justify}

![Flow](/assets/img/4_interactive_asset.png){:width="400px"}

An interactive tool for user-customized rendering. The system automatically provides the result but the user can adjust the output through the interface. The user can wear some pre-defined accessories to the face. We provide glasses, tattoos, and hat options.
{: .text-justify}


### Result

![Flow](/assets/img/5_result.png){:width="400px"}

Our system captures the user's face via surrounding cameras, then generates a detailed photo-realistic face scan that can be deformed in real-time without relying on face templates. Our final result is shown as above.
{: .text-justify}

<iframe
        width="100%" height="315" src="https://www.youtube.com/embed/aaCEkpZXNpA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen>
</iframe>

This is the demo video on our proposed Face Clone system.
{: .text-justify}
