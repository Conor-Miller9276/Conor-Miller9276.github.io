---
title: "About Me"
layout: default
permalink: /about-me/
---
skills:
  -name: "Unity"
   icon: "fab fa-fw fa-unity"
   badges: ["C#", "Game Dev"]
   text: "Hallo"
   years: 2
  -name: "Game Design"
   icon: "fas fa-fw fa-gamepad"
   badges: ["Game Mechanics", "Levels", "UI"]
   text: "Hallo 2"
   level_label: "Noob"
---
{% include skills skills=page.skills %}



{% include figure image_path="/assets/images/TBOI.png" alt="Game Jam screenshot" caption="This is a caption" %}

{% include download
  title="Download my Project Proposal"
  url="/assets/downloads/Project-proposal.pdf"
  button_label="Download Project Proposal"
  download="Project-proposal.pdf"
%}


