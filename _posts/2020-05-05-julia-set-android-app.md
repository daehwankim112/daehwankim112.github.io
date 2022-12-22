---
title: Julia Set Android App
date: 2020-05-05 21:00:00 -0800
categories: [Projects, Andoird App Julia Set]
tags: [game,julia,mandelbrot,fractal,set,android,app,application,play,store,"2020",challenge,daehwan,kim,david]     # TAG names should always be lowercase
---

# My First Android App 2020

![Desktop View](/assets/images/julia/image1.png){: width="100%" }

I made an android app that user can simulate Julia set in 2020 May. So far, in 2022 December, more than 500 downloads have been recorded. I was interested in how far we could zoom in in mandelbrot set. I wanted to make a simulation of madelbrot set and push its limit on android device. Later, running a fractal on an andriod device was more expensive than my expection that I changed direction and built Julia set simulation instead.

## What is Julia Set?

Numberphile did a great explanation video about Mandelbrot Set and Julia Set. Please check their videos.
<div class = "video-container">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/NGMRB4O922I" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

_Mandelbrot Set by Numberphile_

<div class = "video-container">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/oCkQ7WK7vuY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

_Julia Set by Numberphile_


## What was your app about?
<div class = "video-container">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/9PoNSOJ1OT4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

_Preview of my app on <a href="https://play.google.com/store/apps/details?id=com.DaehwanKim.JuliaSet">google playstore</a>_

It is a simulation of Julia Set. User can
* Drag around
* Change periods of RGB colors in sin function
* Toggle auto-color change
* Change real and imaginary value of C
* Toggle C value to be 0.7885*e^(ia) where a =[0, 2pi]


## Challenges

* This app is developed using Unity Engine. I wish I could have made it without using an already existing engine. However, I did not know where to begin. The development process was highly dependent on <a href="https://youtu.be/kY7liQVPQSc">The Art of Code</a>.

## What have you learned?

![Desktop View](/assets/images/julia/image2.png){: width="100%" }
_Installed audience by country_

It is possible to build an app using unity. However, I lack fundamental knowledge in unity itself. Furthermore, optimization is an issue on the android platform. I targetted user persona to be my friends, but apparently there are more people who are using my app than my expectations.


### Source Code
<a href="https://github.com/daehwankim112/Mandelbrot">https://github.com/daehwankim112/Mandelbrot</a>

### The app on Playstore
<a href="https://play.google.com/store/apps/details?id=com.DaehwanKim.JuliaSet">https://play.google.com/store/apps/details?id=com.DaehwanKim.JuliaSet</a>

<style>
    .video-container {
        position: relative;
        padding-bottom: 56.25%; /* 16:9 */
        height: 0;
    }
    .video-container iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }


