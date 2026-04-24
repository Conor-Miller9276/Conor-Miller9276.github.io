---
title: "About me"
layout: default
permalink: /about-me/
classes: wide
skills:
  - name: "Unity"
    icon: "fab fa-fw fa-unity"
    badges: ["C#", "Game Dev"]
    text: "Developed 2D projects and a 3D project"
    level_label: "Beginner"
  - name: "Game Design"
    icon: "fas fa-fw fa-gamepad"
    badges: ["Game Mechanics", "Levels", "UI"]
    text: "Designed levels for 2D projects, 3D project and boardgame"
    level_label: "Beginner"
  - name: "Godot"
    icon: "fa-solid fa-code"
  - name: "Aseprite"
    icon: "fa-solid fa-pen"
  - name: "Composition"
    icon: "fa-solid fa-music"
---


<div style="display:flex; flex-wrap:wrap; gap:4rem; align-items:flex-start;">
<!-- LEFT: text content -->
<div style="flex:1 3 100px; min-width:500px;">
<h2>1st yr Project Game - 2D Platformer</h2>
<p>
Hi, my name is conor miller and i am a current first year game design and development student at ulster university. Im learning C# in university and outside university i am learning godot for a personal project. i have developed three projects being a 2D game, a board game and a 3D environment. 
</p>
Below you can see the list of skills i have been developing over the last year and the level i am at. You will also find a form where you can get in contact with me. To view my created projects visit the "projects" page.
  
</p>
</div>
</div>
<h2>Skills: </h2>

{% include skills skills=page.skills %}


{% include google-form title="Contact Me" src="https://docs.google.com/forms/d/e/1FAIpQLSffZskfUT8YVC6h5DTIdtDJadT6VnGyeHvYshWXojvCU5FeGA/viewform?usp=publish-editor" height="800" %}

{% include download
  title="Download my Project Proposal"
  url="/assets/downloads/Project-proposal.pdf"
  button_label="Download Project Proposal"
  download="Project-proposal.pdf"
%}




