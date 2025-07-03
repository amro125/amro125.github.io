---
title: Safe And Sound
description: NSF funded project using music to improve safety and fluency in human robot interaction
category: Studies, Human Robot Interaction
# date: 2022-01-05 08:01:35 +0300
role: Project Lead, Programmer, Studies
image: '/images/SASRobot3.png'
image_caption: ''
# featured: true
---

Safe and Sound is a project I helped write an NSF funded grant for! In this project, we are using music to improve safety and fluency. Currently, modern robot sonification consists of repetitive beeps (think of a truck backing up) that can become annoying to listen to for  longer than a few seconds. Hospitals have similar issues where they have many beeps that demand attention all the time (even when they don't need it) which can cause healthcare workers to grow anxious or even tone out sounds (called alarm fatigue). 

Conversely, people can listen to music for hours and extract a lot of information without growing bored or becoming desensitized. If you look at the lofi girl youtube channel, people listen to it for hours on end. Our goal is generate songs that can modify specific musical features ( such as tension and rhythmic stability) to communicate the danger and urgency level of a robot, without constantly demanding our attention.

 This does mean that the sound will become urgent when the robot will crash, but if the robot is moving heavy payloads, its good to know the danger but no one needs to shout it at me. In other words,  I can listen to my lofi robot music: 

 > If I wanna know the status of my robot I pay attention to the music a little more, but if I wanna focus on my work, the robots music will not distract me. If the robot requires my focus,  it will  change the rhythm in a way to catch my attention. 
 
 We first gathered data of music clips to understand the relationship between higher level musical features and safety and urgency. Based on this we came up with a framework to generate safe audio

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/framework.png" loading="lazy" alt="Work">
  </div>
  <em>Framework to sonify robots with high level music features</em>
</div>

 To improve fluency and coordination between users and robot, I'm leveraging predictable elements of music for  humans and robots to sync their task to (for example, the pop goes the weasel melody, or if you are a Bostonian everyone knows when to shout ""BUM BUM BUM" after "sweeeeeet caaaaaroliiiine"). We can predict when the last BUM of Sweet Caroline is and then hand an object to the robot. Lastly, Since I love hardware, Im also working on a cool new way to present this audio to users, so stay tuned for that!

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/FluencySystemOverview.png" loading="lazy" alt="Work">
  </div>
  <em>Overview on fluency to improve synchronization</em>
</div>

We are also working on some cool hardware applications to embed the audio of this project!

## Relevant Publications
<em><a href="https://ieeexplore.ieee.org/abstract/document/10973803?casa_token=6em6fV0E-poAAAAA:ezkieyYKESSMa2Rtl8YB4n1bjrqJiTZdP4Ypcul9xhRuBvH320iUlTiZxP6t9RgPGof1UEmM" target="_blank">What Sounds Dangerous? Establishing Correlations Of Musical Features and Perceived Safety in HRI</a></em>
<br>Amit Rogel, Jack Haley, Richard Savery, Gil Weinberg
<br><strong> 2025 HRI Conference</strong>

<em><a href="https://ieeexplore.ieee.org/abstract/document/10973803?casa_token=6em6fV0E-poAAAAA:ezkieyYKESSMa2Rtl8YB4n1bjrqJiTZdP4Ypcul9xhRuBvH320iUlTiZxP6t9RgPGof1UEmM" target="_blank">Do Re Mi Fa So Pass the tool? Using Melodic Prediction to Improve Human-Robot Fluency </a></em>
<br>Amit Rogel, Jack Haley, Gil Weinberg
<br><strong> 2025 RoMan Conference</strong>

<!-- ## Other Media
<em><a href="https://ieeexplore.ieee.org/document/10491398" target="_blank">IEEE Spectrum</a></em>
<br> Published 2024
<br><strong>IEEE highlight</strong> -->


