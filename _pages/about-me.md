---
title: "About Me"
layout: single
permalink: /about-me/
gallery_gameplay:
  # Recommended: width "240px" to "320px" keeps a neat grid
  - url: /assets/images/placeholder.png
    image_path: /assets/images/placeholder.png
    alt: "Gameplay 1"
    title: "Tilemaps"
    caption: "Tilemaps"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/placeholder.png
    alt: "Gameplay 2"
    title: "Player Sprites"
    caption: "Player Sprites"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/placeholder.png
    alt: "Gameplay 3"
    title: "Power-ups"
    caption: "Power-ups"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/placeholder.png
    alt: "Gameplay 4"
    title: "Enemy Design"
    caption: "Enemy Design"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/placeholder.png
    alt: "Gameplay 5"
    title: "Map Design"
    caption: "Map Design"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/placeholder.png
    alt: "Gameplay 6"
    title: "Programming"
    caption: "Programming"
skills:
  - name: "Unity"
    icon: "fab fa-fw fa-unity"
    badges: ["Game Dev"]
    text: "Developed several 2D and 3D games in the Unity Engine"
    years: 1
  - name: "Level Design"
    icon: "fas fa-fw fa-gamepad"
    badges: ["Levels"]
    text: "Proficient in the creation of game levels and maps"
    level_label: "Beginner"
  - name: "Coding"
    icon: "fab fa-fw fa-unity"
    badges: ["C#"]
    text: "Proficient in the use and integration of C# for game development"
    years: 1
  - name: "Game Art"
    icon: "fab fa-fw fa-unity"
    badges: ["Libresprite"]
    text: "An understanding of the tools needed to create game art, mainly pixel art"
    years: 1
---

I am Christopher Lightwood, a first year Games Design and Development student at Ulster University.

## Some of my work
{% include gallery id="gallery_gameplay" layout="third" thumb_height="180px" %}

## Some of my key skills
{% include skills skills=page.skills %}
