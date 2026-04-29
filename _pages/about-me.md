---
title: "About Me"
layout: single
permalink: /about-me/
gallery_gameplay:
  # Recommended: width "240px" to "320px" keeps a neat grid
  - url: /assets/images/placeholder.png
    image_path: /assets/images/AMGallery5.png
    alt: "Gameplay 1"
    title: "Tilemaps"
    caption: "Tilemaps"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/AMGallery1.png
    alt: "Gameplay 2"
    title: "Player Sprites"
    caption: "Player Sprites"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/Games-Creation.png
    alt: "Gameplay 3"
    title: "Board Games"
    caption: "Board Games"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/AMGallery2.png
    alt: "Gameplay 4"
    title: "Enemy Design"
    caption: "Enemy Design"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/AMGallery4.png
    alt: "Gameplay 5"
    title: "Map Design"
    caption: "Map Design"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/AMGallery3.png
    alt: "Gameplay 6"
    title: "Programming"
    caption: "Programming"
skills:
  - name: "Unity"
    icon: "fab fa-fw fa-unity"
    badges: ["Game Dev"]
    text: "Developed several 2D and 3D games in the Unity Engine"
    year: 1
  - name: "Level Design"
    icon: "fa-solid fa-map"
    badges: ["Levels"]
    text: "Proficient in the creation of game levels and maps"
    year: 1
  - name: "Coding"
    icon: "fas fa-fw fa-gamepad"
    badges: ["C#"]
    text: "Proficient in the use and integration of C# for game development"
    year: 1
  - name: "Game Art"
    icon: "fa-solid fa-paint-roller"
    badges: ["Libresprite"]
    text: "An understanding of the tools needed to create game art, mainly pixel art"
    year: 1
---

I am Christopher Lightwood, a first year Games Design and Development student at Ulster University.

## Some of my work
{% include gallery id="gallery_gameplay" layout="third" thumb_height="180px" %}

## Some of my key skills
{% include skills skills=page.skills %}
