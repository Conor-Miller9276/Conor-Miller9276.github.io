---
title: "About me"
layout: default
permalink: /about-me/
classes: wide
skills:
  - name: "Unity"
    icon: "fab fa-fw fa-unity"
    badges: ["C#", "Game Dev"]
    text: "Have developed 2 2D projects and a 3D landscape"
    level_label: "Beginner"
  - name: "Game Design"
    icon: "fas fa-fw fa-gamepad"
    badges: ["Game Mechanics", "Levels", "UI"]
    text: ""
    level_label: "Noob"
  - name: "Godot"
    icon: "fa-solid fa-code"
---


<div style="display:flex; flex-wrap:wrap; gap:4rem; align-items:flex-start;">
<!-- LEFT: text content -->
<div style="flex:1 1 100px; min-width:300px;">
<h2>1st yr Project Game - 2D Platformer</h2>
<p>
Hi, my name is conor miller and i am a current first year game design and development student at ulster university. I have developed many skills throughout this course as im learning C# in university and outside university i am learning godot for a personal project. i have developed three projects being a 2D game, a board game and a 3D environment. 
  
</p>
</div>

<h2>Skills: </h2>

{% include skills skills=page.skills %}

<h3>Contact Me: </h3>
{% include google-form title="Contact Me" src="https://forms.gle/XsbApFoRjn7r24jy6" height="1500" %}

<p align="centre">
{% include download
  title="Download my Project Proposal"
  url="/assets/downloads/Project-proposal.pdf"
  button_label="Download Project Proposal"
  download="Project-proposal.pdf"
%}


