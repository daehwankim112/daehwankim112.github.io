---
title: MRI to 3d Model
date: 2023-01-30 21:00:00 -0800
categories: [Projects, MRI to 3d Model]
tags: [mri,"3d",scan,model,ct,bone,disc,slicer,blender,"2023",victoria,university,daehwan,kim,david]     # TAG names should always be lowercase
---

# Hmm.. What can I do with my MRI?

<div class="sketchfab-embed-wrapper"> <iframe title="Spinal Cord [bones and discs]" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share src="https://sketchfab.com/models/f2225d4988b04b45848440f27a027342/embed"> </iframe> <p style="font-size: 13px; font-weight: normal; margin: 5px; color: #4A4A4A;"> <a href="https://sketchfab.com/3d-models/spinal-cord-bones-and-discs-f2225d4988b04b45848440f27a027342?utm_medium=embed&utm_campaign=share-popup&utm_content=f2225d4988b04b45848440f27a027342" target="_blank" style="font-weight: bold; color: #1CAAD9;"> Spinal Cord [bones and discs] </a> by <a href="https://sketchfab.com/daehwankim?utm_medium=embed&utm_campaign=share-popup&utm_content=f2225d4988b04b45848440f27a027342" target="_blank" style="font-weight: bold; color: #1CAAD9;"> daehwankim </a> on <a href="https://sketchfab.com?utm_medium=embed&utm_campaign=share-popup&utm_content=f2225d4988b04b45848440f27a027342" target="_blank" style="font-weight: bold; color: #1CAAD9;">Sketchfab</a></p></div>



On September 1st, 2022, I took an MRI of my spinal cord. The doctor showed me my spinal cord on the screen and gave me the MRI scan on CD. Then I met <a href="https://www.linkedin.com/in/marianne-black-4518a523/?originalSubdomain=ca">Dr. Marianne Black</a> on January 11th 2023. She showed me a musculoskeletal 3D model she had created based on an MRI scan. Her works are very inspiring and motivated me to work on this.

## What is MRI?

![Desktop View](/assets/images/mri/image1.png){: width="100%" }

MRI (Magnetic Resonance Imagining) is a medical imagining technique used in radiology to form pictures of the anatomy and the physiological processes of the body. Using MRI scans, doctors can detect certain diseases by better understanding of the inner situation of patients.

<!---
<div class = "video-container">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/7uyGG5ffw5o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
--->

## Prepare the working environment.

1. Copy the whole CD into a PC.
2. <a href="https://download.slicer.org/">Download 3D Slicer</a>. It works for Windows and Linux.
3. <a href="https://www.blender.org/">We need Blender</a>.

## How to make MRI scan to 3d model

1. Import Dicom Database into <a href="https://www.slicer.org/">3D Slicer</a>. We can find this option in 3D Slicer.
2. Segment the sections where we want to model using tools including: paint, erase, threshold, and level tracing. I've found level tracing very useful.
3. Show 3D to preview the model.
4. Export in STL file format.
5. Import STL file into Blender.
6. Trim the model.
* It is an enormous file. Reduce the number of polygons.
* Remove unconnected vertices, edges, and faces.
* Color it using material for better visibility.
7. Save in Obj file format.
8. Upload the Obj file on Sketchfab. (optional)

## What have you learned?

<div class="sketchfab-embed-wrapper"> <iframe title="Spinal Cord [discs]" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share src="https://sketchfab.com/models/379ce1dbe7e646459ba3210e054f06f0/embed"> </iframe> <p style="font-size: 13px; font-weight: normal; margin: 5px; color: #4A4A4A;"> <a href="https://sketchfab.com/3d-models/spinal-cord-discs-379ce1dbe7e646459ba3210e054f06f0?utm_medium=embed&utm_campaign=share-popup&utm_content=379ce1dbe7e646459ba3210e054f06f0" target="_blank" style="font-weight: bold; color: #1CAAD9;"> Spinal Cord [discs] </a> by <a href="https://sketchfab.com/daehwankim?utm_medium=embed&utm_campaign=share-popup&utm_content=379ce1dbe7e646459ba3210e054f06f0" target="_blank" style="font-weight: bold; color: #1CAAD9;"> daehwankim </a> on <a href="https://sketchfab.com?utm_medium=embed&utm_campaign=share-popup&utm_content=379ce1dbe7e646459ba3210e054f06f0" target="_blank" style="font-weight: bold; color: #1CAAD9;">Sketchfab</a></p></div>

Blender is a useful tool for 3D modeling. It could also be used for modelling, rigging, and animations. Especially, rigging is an important process to build moving objects in VR environments. When a user tries a new avatar for motion tracking and if calibration does not fix the drifting or breaking issues, the developer should locate the bugs in Unity or Blender and fix them.


## Challenges

* Using 3D Slicer to build 3D model could take a lot of time. Next time, find, or build a better solution.
* Learning blender gives me tremendous power to fix issues and express my creativity. Learn more about it.

### Source Code
<a href="https://github.com/daehwankim112/MRI_to_3D_model">https://github.com/daehwankim112/MRI_to_3D_model </a>

### Dr. Marianne Black
<a href="https://www.linkedin.com/in/marianne-black-4518a523/?originalSubdomain=ca">https://www.linkedin.com/in/marianne-black-4518a523/?originalSubdomain=ca</a>


<style>
    .sketchfab-embed-wrapper iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }
</style>

