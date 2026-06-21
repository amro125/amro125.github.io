---
title: MI Blocks
order: 2
description: A LEGO compatible interactive system for kids to learn sensor mapings and music
category: Interactive Music System
role: Designer, Hardware
image: '/images/miBirds.jpg'
image_caption: 'Mi Blocks on system'
featured: true
---

MI Bocks, or Music Interactive Blocks, are a LEGO-inspired/compatible electronic music interface that utilizes a limited musical vocabulary to scaffold novices in early compositional decision-making for electronic music making.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/coolpic.jpg" loading="lazy" alt="Work" style="max-width: 400px; width: 100%;">
  </div>
  <em style="text-align: center;">MI Block Steup </em>
</div>

### Design Philosophy

The paradigm of "Active Learning" for music education often prioritizes self-exploration and learning through experience before introducing any theory. The *Orff instrumental set*, first developed in 1928, is a set of simple, toy-like percussion instruments, little drums, tambourines, xylophones, and glockenspiels, designed to invite and encourage children to play music together in simplified settings within a classroom. They are among the most widely used tools in early musical education. The success of the Orff instrument set can be attributed to its *simple and intuitive* designs that resonated with children.


> “Children learn through play and adults play through art.”


Currently, there is a growing motivation to develop digital early music education tools that combine the toy-like design language of Orff instruments with the open-ended potential for musical exploration and engagement afforded by electronic music practices. This project uses the familiarity and modularity of LEGO for interactive musical systems; users can place Music Interactive (MI) Blocks on a board. When a block is placed on a board, any sensor data on the block immediately starts streaming. These values are filtered and start premapped to a musical feature, but can be modified for the users need

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/MiSonar.JPG" loading="lazy" alt="Work" style="max-width: 400px; width: 100%;">
  </div>
  <em style="text-align: center;">Three MI Block sensors </em>
</div>


### System design 

The overall system design for the Modular LEGO musical interface parallels LEGO Mindstorm robotics invention system. Our system includes a microcontroller core that handles the logic and processes streams of data from sensor modules that are physically compatible with standard LEGO building elements.


This project was in a collaboration with Noel Alban, with an original prototype featuring only legos connected to a microcontroller. We wanted to redesign the system with a more user friendly interface. In the original system, every sensor hooked up had to be manually plugged into an arduino board (which also resulted in a mess of cables). Additionally, the software was cpp based which is not as visual for kids to play with. The new system uses magnets to snap miblocks in place, and embeds a microcontroller on each block. This allows us to wirelessly stream the data to any host. 

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/protomi.jpg" loading="lazy" alt="Project">
    <img src="/images/kids.png" loading="lazy" alt="Project">
    
    <!-- <img src="/images/forest13.jpg" loading="lazy" alt="Project"> -->

  </div>
  <em>Prototyped Version</em>
</div>

We received a seed grant of $2,000 for this project and debuted it in a concert in May 2026. Afterwards, people were able to interact with the system and play with it


<div class="gallery-box">
  <div class="gallery">
    <img src="/images/mikid.JPG" loading="lazy" alt="Project">
    <img src="/images/miconcert.JPG" loading="lazy" alt="Project">
    <img src="/images/miguitar.JPG" loading="lazy" alt="Project">
  


  </div>
  <em>MI Block Concert</em>
</div>

<!-- ## Relevant Publications

<em><a href="https://www.taylorfrancis.com/chapters/edit/10.1201/9781003320470-13/robotic-dancing-emotional-gestures-prosody-framework-gestures-three-robotic-platforms-richard-savery-amit-rogel-gil-weinberg" target="_blank">Robotic Dancing, Emotional Gestures and Prosody: A Framework for Gestures of Three Robotic Platforms</a></em>
<br>Amit Rogel, Richard Savery, Gil Weinberg
<br><strong>Sound and Robotics Book Chapter</strong>


## Other Media

<em><a href="https://www.scientificamerican.com/article/want-to-get-humans-to-trust-robots-let-them-dance/" target="_blank">Want to Get Humans to Trust Robots? Let Them Dance</a></em>
<br> Published 2021
<br><strong>Scientific American</strong>

<em><a href="https://spectrum.ieee.org/robot-dance-music" target="_blank">Building Human-Robot Relationships Through Music and Dance</a></em>
<br> Published 2021
<br><strong>IEEE Spectrum</strong>

<em><a href="https://research.gatech.edu/finding-their-groove" target="_blank">Finding Their Groove</a></em>
<br> Published 2021
<br><strong>University Article</strong>

<em><a href="https://la.mathworks.com/company/mathworks-stories/ga-tech-robots-build-trust-through-dance.html" target="_blank">A Forest of Robots Builds Trust Through Dance</a></em>
<br> Published 2021
<br><strong>Mathworks Article</strong>

<em><a href="https://research.gatech.edu/finding-their-groove" target="_blank">Finding Their Groove</a></em>
<br> Published 2021
<br><strong>University Article</strong> -->

