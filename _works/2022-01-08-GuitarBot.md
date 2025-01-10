---
title: Expressive Robotic Guitar
description: An acoustic guitar-playing robot that mimics huuman motion to play expressive 
category: Robotic Musician
date: 2022-01-08 08:01:35 +0300
client: Music Festival
# role: 
image: '/images/guitarbot.jpg'
image_caption: 'Expressive Robot Guitar'
---
 Expressive Robotic Guitar (ERG) is designed to play a commercial acoustic guitar while controlling a wide dynamic range, millisecond-level note generation, and a variety of playing techniques such as strumming, picking, overtones, and hammer-ons. To allow for these functionalities, we recorded and modeled human guitarists and implemented our findings in hardware and software design. The ERG's final construction includes a robotic cobot arm for strumming and plucking, as well as a 12-motor fret-shifting module that can move across the guitar bridge.
 
 The ERG holds a special place in my heart as this was the first robotic musician I made from scratch. Most of my  efforts were focused on the left hand design and construction of the robot. We wanted to build a system based on three key robot goals: 

> Firstly, the robot must play acoustic sound and capture subtle guitarist features. Secondly, the robot will play techniques that a human typically would not play. Lastly, playing the guitar will be visually appealing and engaging to audience members; this will also help musicians see when the robot is about to play. 
<div class="gallery-box">
  <div class="gallery">
    <img src="/images/lefthand.jpg" loading="lazy" alt="Work">
  </div>
  <em>Design of overall left hand</a></em>
</div>

The left hand design has the sliders for each presser offset from the fret,so audience members can still see the instrument, and the chord shape of the robot. Each slider can also move independently which allows us to create unique finger patterns for chords (fun fact, there are 1072 different ways the guitarbot can play A major 7 chords usign the ten frets and any of the 6 strings).

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/finger_explode.jpg" loading="lazy" alt="Work">
    <img src="/images/pick_explode.jpg" loading="lazy" alt="Work">
  </div>
  <em>individual design of string manipulation </a></em>
</div>

 The pressing mechanism uses a cam design to save space, and gives us more travel time to do hammer-ons. The picking system mimics a human wrist, but the pick can perform tremolo at 120 Hz. 

This video was the original version of the guitarbot before the left hand, showinf off some of the tremolo features of our picking mechnism. 

<p><iframe src="https://www.youtube.com/embed/llHC-jus1GA?si=OyTchPsU_gDLLSwj" loading="lazy" frameborder="0" allowfullscreen></iframe></p>

We switched to using an xArm 7 and added the left hnd for the current version


We are also now working with Derrick Joyce and Marcus Parker to develope a new picking mechanismto pick all 6 strings in  visually appealing way. 



## Relevant Publications
<em><a href="https://ieeexplore.ieee.org/abstract/document/10251619" target="_blank">Design of an expressive Robot Guitarist</a></em>
<br>Ning Yang, Amit Rogel, Gil Weinberg
<br><strong>Robotics Automation Letter (RAL)</strong>

## Other Media
<em><a href="https://research.gatech.edu/feature/robot-guitarist" target="_blank">Robot Guitarist Plays With Human Expressivity</a></em>
<br> Published 2023
<br><strong>University Article</strong>