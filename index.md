---
title: "Hi!"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0"
  overlay_image: /assets/images/home-page-feature.png
  actions:
    - label: "Feel free to contact me"
      url: "mailto:nicolacognata@gmail.com"
  caption: "Image credit: [**Conner Ramputi**](https://phogen.artstation.com/) and Christian Babcock"
excerpt: "You've stumbled across my portfolio. I'm a recent graduate from the University of Central Florida looking to dive head first into the industry. I love making games and running on the edge of what the hardware is capable of. <br/><br/>Below you'll find a collection of some of my personal and professional work."
shimahara_row:
  - image_path: /assets/images/CarolinaYards.jpg
    alt: "Carolina Yards"
    title: Turnbridge Carolina Yards
    excerpt: 'I was recently hired as a Gameplay Programming Contractor to develop some tools for [Shimahara Visual](http://shimaharavisual.com/), an architectural visualization firm. I developed an Unreal Engine 4 plugin stuffed with gameplay tools to enable their artists to iterate on their project more rapidly. I worked closely with one of their artists to develop interactive camera rigs, player controls, and custom UI elements with the features they needed to get the job done. '
screwjank_row:
  - image_path: /assets/images/screwjank-logo.jpg
    alt: "Screwjank Games Logo"
    title: "Screwjank Games"
    excerpt: Since I'm trapped inside my own home due to a global pandemic, I've put my spare time to use by over-engineering my second attempt at making a [game engine](https://github.com/ScrewjankGames/ScrewjankEngine). It's written with C++20 in mind, and recently received a shiny new set of [custom memory allocators](https://screwjankgames.github.io/engine%20programming/2020/09/24/writing-your-own-memory-allocators.html).
    url: "https://screwjankgames.github.io/"
    btn_label: "Read More"
    btn_class: "btn--primary"
computron_row:
  - image_path: /assets/images/computron.jpg
    alt: "Computron"
    title: "Computron"
    excerpt: Computron is a 2D puzzle game developed using Unity. It was my degree's capstone project, which I pitched and convinced a team of three other programmers (and later two artists) to develop with me. The game focuses on providing players a gentle introduction to the world of computational thinking and problem solving. This year me and another programmer from the team handed the project over to a new set of students, and we are serving as their advisors. If you'd like to play the game you can download it [here](https://drive.google.com/open?id=1Zd70CsJta8AJ_XGvRc81Er-DYy5SdbWq), or play the **unstable** WebGL deployment of our game by clicking the button below
    url: "https://cop4934-fall19-group32.github.io/"
    btn_label: "Computron WebGL Player"
    btn_class: "btn--primary"
supervoid_row:
  - image_path: /assets/images/SuperVoidDemo.gif
    alt: "SuperVoid"
    title: "SuperVoid"
    excerpt: "SuperVoid is an Asteroids-like game I built, powered by a game engine I wrote from scratch using OpenGL 4.5 and C++. The engine's features include: <br/>
     - A custom renderer <br/>
     - A custom physics engine <br/>
     - A custom Entity-Component system <br/>
     - Multithreading support <br/>
     - Asynchronous file I/O <br/>
     - Resource Caching <br/>
    <br/><br/>If you'd like to see the engine code, click the button below."
    url: "https://github.com/MrLever/VoidEngine"
    btn_label: "VoidEngine"
    btn_class: "btn--primary"
master_blaster_row:
  - image_path: /assets/images/master-blaster.jpg
    alt: "MasterBlaster"
    title: "Master Blaster"
    excerpt: MasterBlaster was my first real game project, developed for a course I was taking at UCF. It's a 2D [Steamworld Heist-like](https://store.steampowered.com/app/322190/SteamWorld_Heist/) turn-based strategy game. I worked with a team of two other programmers to rapidly develop the game in Unreal Engine 4 over the course of a semester, and was responsible for the game's level generator, AI, and art.
    url: "https://github.com/Team-11-Games/MasterBlaster"
    btn_label: "Game Repository"
    btn_class: "btn--primary"
---

<!-- {% include feature_row id="intro" type="center" %} -->

# **Professional Projects**
{: style="text-align: center;"}
<hr/>
<br/>

{% include feature_row id="shimahara_row" type="right" %}

<br/>

# **Personal Projects**
{: style="text-align: center;"}
<hr/>
<br/>
{% include feature_row id="screwjank_row" type="left" %}
{% include feature_row id="computron_row" type="right" %}
{% include feature_row id="supervoid_row" type="left" %}
{% include feature_row id="master_blaster_row" type="right" %}
<!-- {% include feature_row id="feature_row4" type="center" %} -->
