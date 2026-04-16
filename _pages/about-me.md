---
title: "About me"
layout: default
permalink: /about-me/
classes: wide
gallery_gameplay:
  # Recommended: width "240px" to "320px" keeps a neat grid
  - url: /assets/images/3D Inside House.png
    image_path: /assets/images/3D Inside House.png
skills:
  - name: "Unity"
    icon: "fab fa-fw fa-unity"
    badges: ["C#", "Game Dev"]
    text: "Hallo"
    years: 2
  - name: "Game Design"
    icon: "fas fa-fw fa-gamepad"
    badges: ["Game Mechanics", "Levels", "UI"]
    text: "Hallo 2"
    level_label: "Noob"
  - name: "Godot"
    icon: "fa-solid fa-code"
  - name: "Godot"
    icon: "fa-solid fa-code"
  - name: "Godot"
    icon: "fa-solid fa-code"
  - name: "Godot"
    icon: "fa-solid fa-code"
---


<div style="display:flex; flex-wrap:wrap; gap:4rem; align-items:flex-start;">
<!-- LEFT: text content -->
<div style="flex:1 1 100px; min-width:400px;">
<h2>1st yr Project Game - 2D Platformer</h2>
<p>
Hi, my name is conor miller and i am a current first year game design and development student at ulster university. I have developed many skills throughout this course as im learning C# in university and outside university i am learning godot for a personal project. i have developed three projects being a 2D game, a board game and a 3D environment.
</p>
</div>

<h2>Skills: </h2>

{% include skills skills=page.skills %}

{% include gallery id="gallery_gameplay" layout="third" thumb_height="180px" %}


{% include download
  title="Download my Project Proposal"
  url="/assets/downloads/Project-proposal.pdf"
  button_label="Download Project Proposal"
  download="Project-proposal.pdf"
%}


