---
layout: page
title: Sign Gesture Translator
description: Two models that helps convert sign language into text~
img: assets/img/sign_language_project.jpg
importance: 2
category: Robotics
---

***

<style>
.video-holder {
  position: relative;
  width: 100%;
  height: 0;
  padding-bottom: 56.25%;
  overflow: hidden;
}
.video-holder iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
</style>

<h3 style="text-align:center"> Translating Numbers in Hand Gesture </h3>

<div class="video-holder">
  <iframe width="560"
          height="315" 
          src="https://www.youtube.com/embed/PmTjQT3sj9w" 
          frameborder="0" 
          allowfullscreen></iframe>
</div>
<hr>
<h3 style="text-align:center"> Translating Sign Alphabet in Hand Gesture </h3>

<div class="video-holder">
  <iframe width="560"
          height="315" 
          src="https://www.youtube.com/embed/WWyAAuIuly4" 
          frameborder="0" 
          allowfullscreen></iframe>
</div>


<hr>
<h2 style="text-align:center"> What It Does </h2>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/hand_gesture_project.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/sign_language_demo.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

As you can see from the videos, I have basically trained two models that can <b>translate hand gestures</b> for numbers and alphabets into texts. 
The model for the second usage(alphabets) might look a bit slow and this is due to the large data that has been provided and the small cpu running it, but hey it works :) 

Although these are just some fun projects, but I also believe they have the potential to carry out<b> real-world application values </b> as they can contribute to numerous interesting applications such as:
<ul class="fa-ul">
  <li><i class="fa-li fa fa-check-square"></i>helping to teach people with handicap the alphabet</li>
  <li><i class="fa-li fa fa-check-square"></i>creating apps facilitating communications/translations</li>
</ul>

