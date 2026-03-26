---
title: "About Me"
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

inner: {
width: 75%;
}
---


<div style="display:flex; flex-wrap:wrap; gap:4rem; align-items:flex-start;">
<!-- LEFT: text content -->
<div style="flex:1 1 950px; min-width:250px;">
<h2>1st yr Project Game - 2D Platformer</h2>
<p>
As part of a team, I helped design and build a 2D Platform game for my course
in module CRE135: 2D Game Creation.
</p>
</div>
<!-- RIGHT: video/content area -->
<div style="flex:1 1 250px; min-width:250px;">
<!-- Replace this placeholder with a YouTube iframe or a video tag -->
{% include video id="dQw4w9WgXcQ" provider="youtube" %}
</div>
</div>

{% include skills skills=page.skills %}

{% include figure image_path="/assets/images/TBOI.png" alt="Game Jam screenshot" caption="This is a caption" %}
{% include figure image_path="/assets/images/TBOI.png" alt="Game Jam screenshot" caption="This is a caption" %}

{% include download
  title="Download my Project Proposal"
  url="/assets/downloads/Project-proposal.pdf"
  button_label="Download Project Proposal"
  download="Project-proposal.pdf"
%}


