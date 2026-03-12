---
title: "James Tiernan - Game Dev Portfolio"
layout: splash
permalink: /
gallery_gameplay:
  # Recommended: width "240px" to "320px" keeps a neat grid
  - url: /assets/images/gallery (1).png
    image_path: /assets/images/gallery (1).png
    
  - url: /assets/images/gallery (2).png
    image_path: /assets/images/gallery (2).png

  - url: /assets/images/gallery (3).png
    image_path: /assets/images/gallery (3).png

  - url: /assets/images/gallery (4).png
    image_path: /assets/images/gallery (4).png

  - url: /assets/images/gallery (5).png
    image_path: /assets/images/gallery (5).png

  - url: /assets/images/gallery (6).png
    image_path: /assets/images/gallery (6).png

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/banner1.jpg
  actions:
    - label: "Download CV"
      url: "https://drive.google.com/file/d/1SX9zCxM6nMXCKBIflu2NPNMquBtxBdGE/preview"
      target: "_blank"


excerpt: "Welcome to my portfolio site."
intro: 
  - excerpt: 'Experienced in Game Development in Unity using C# and currently studying Games Design and Development at university. Have been creating games for the past 10 years. Developed many solo games over the past 4 years and currently working in a team to build a 2D game in university. Confident programming skills and can quickly adapt to using new programming languages. Skilled in all aspects of games development including Games Design, Art, Programming and Sound Design.'
feature_row:
  - image_path: /assets/images/unity.png
    alt: "Unity"
    title: "Unity"
    excerpt: "Experience in working with Unity in **3D and 2D**. I have created 3+ games using Unity in the past year."
  - image_path: /assets/images/unity.png
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/unity.png
    alt: "placeholder image 4"
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include gallery id="gallery_gameplay" layout="third" thumb_height="230px"%}

