---
title: "James Tiernan - Game Dev Portfolio"
layout: splash
permalink: /

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/banner1.jpg
  actions:
    - label: "Download CV"
      url: "https://drive.google.com/file/d/1SX9zCxM6nMXCKBIflu2NPNMquBtxBdGE/preview"
      target: "_blank"

feature_row:
  - image_path: /assets/images/unity.png
    alt: "Unity"
    title: "Unity"
    excerpt: "Experience in working with Unity in **3D and 2D**. I have created 3+ games using Unity in the past year."
  - image_path: /assets/images/2d-art.png
    alt: "2D Art"
    title: "2D Art"
    excerpt: "Experience in creative 2D art in Pixel and Vector art styles."
  - image_path: /assets/images/3d-art.png
    alt: "3D Art"
    title: "3D Art"
    excerpt: "Experience in creating 3D art using blockbench and blender."
skills:
  - name: "Unity"
    icon: "fab fa-fw fa-unity"
    badges: ["C#", "Game Dev"]
    text: "Built multiple prototypes and participated in game jams."
  - name: "Game Design"
    icon: "fas fa-fw fa-gamepad"
    badges: ["Game Mechanics", "Levels", "UI"]
    text: "Designed mechanics, levels, and player feedback loops."
  - name: "Game Art"
    icon: "fas fa-solid fa-paintbrush"
    badges: ["Level Art", "Libresprite", "Photoshop", "Inkscapes","2D Rigged Character Animation"]
    text: "Experience in creating game art in various styles from Vector, Pixel art and 3D art. Experience in rigging and animating 2D characters."
---
<div style="display:flex; flex-wrap:wrap; gap:2rem; align-items:flex-start;">

  <!-- LEFT: text content -->
  <div style="flex:1 1 250px; min-width:250px;">
    <p>
      Experienced in Game Development in Unity using C# and currently studying Games Design and Development at university. Have been creating games for the past 10 years. Developed many solo games over the past 4 years and currently working in a team to build a 2D game in university. Confident programming skills and can quickly adapt to using new programming languages. Skilled in all aspects of games development including Games Design, Art, Programming and Sound Design.
    </p>
  </div>

  <!-- RIGHT: video/content area -->
  <div style="flex:1 1 250px; min-width:250px;">
    <!-- Replace this placeholder with a YouTube iframe or a video tag -->
    {% include video id="Tc0FzVeg7xc" provider="youtube" %}
  </div>

</div>


{% include feature_row id="intro" type="middle" %}

{% include feature_row %}

{% include skills skills=page.skills %}

