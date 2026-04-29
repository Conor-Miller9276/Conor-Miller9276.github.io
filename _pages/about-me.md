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
    badges: ["Game Mechanics", "Levels", "UI", "GD Script", "Game Dev"]
    text: "Started on a personal project"
    level_label: "Beginner"
  - name: "Aseprite"
    icon: "fa-solid fa-pen"
    badges: ["Pixel Art", "Animation", "UI"]
    text: "Made pixel art for both 2D projects and my Godot personal project"
    level_label: "Beginner"
  - name: "Composition"
    icon: "fa-solid fa-music"
    badges: ["Music", "Composing"]
    text: "Made music for GCSEs"
    level_label: "Beginner"
---


<div style="display:flex; flex-wrap:wrap; gap:4rem; align-items:flex-start;">
<!-- LEFT: text content -->
<div style="flex:1 1 100px; min-width:100px;">
<h2>About Me</h2>
<p>
Hi, my name is conor miller and i am a current first year Game Design and Development student at Ulster University. I'm currently learning C# in University and outside university i am learning godot for a personal project. i have developed three projects being a solo 2D game, a group 2D game and a 3D environment. I have also made a board game.
</p>
Below you can see the list of skills i have been developing over the last year and the level i am at. To view my created projects visit the "projects" page.

</div>
</div>
<h2>Skills: </h2>

{% include skills skills=page.skills %}




