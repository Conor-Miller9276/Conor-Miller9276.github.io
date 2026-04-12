---
title: "About me"
layout: default
permalink: /about-me/
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
---


<div style="display:flex; flex-wrap:wrap; gap:4rem; align-items:flex-start;">
<!-- LEFT: text content -->
<div style="flex:1 1 100px; min-width:250px;">
<h2>1st yr Project Game - 2D Platformer</h2>
<p>
In my first semester as a Game Development student i created a solo game.
</p>
</div>
<!-- RIGHT: video/content area -->
<div style="flex:1 1 250px; min-width:250px;">
<!-- Replace this placeholder with a YouTube iframe or a video tag -->
{% include video id="1ujN925WCDg" provider="youtube" %}
</div>
</div>

<h2>Skills: </h2>

{% include skills skills=page.skills %}

{% include download
  title="Download my Project Proposal"
  url="/assets/downloads/Project-proposal.pdf"
  button_label="Download Project Proposal"
  download="Project-proposal.pdf"
%}


