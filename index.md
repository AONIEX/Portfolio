---
layout: default
title: Home
tags: ["C++", "C#", "Unity", "UE5"]

ongoing:
  - title: "Honours Project"
    description: "3D Sword Procedural Generation, creating historically accurate and visually appealing swords"
    details: "Exploration of algorithms for generating historically accurate blade profiles, crossguards, and hilts in real time."
    image: "Assets/sword2.png"
    link: "Portfolio/honours/"
    tags: ["C++", "Procedural Generation", "Unity", "3D Graphics"]

featured:
  - title: "Synaptic"
    description: "My 3rd year professional project, later showcased at Abertay's Dare Academy."
    details: "A team-developed Unreal Engine 5 title focused on gameplay mechanics, custom C++ systems, and optimization."
    image: "https://github.com/user-attachments/assets/a12b8fc3-fe75-453e-8ef8-0454fba62356"
    link: "Portfolio/projects/#Dare_Academy"
    tags: ["C#", "UE5", "Dare Academy", "Group Project"]

  - title: "Ba Ba BANG! Sheep"
    description: "A first-year project grown into a mobile game, refined each summer."
    details: "An arcade-style mobile title built in Unity featuring touch controls, score tracking, and performance passes for Android."
    image: "https://github.com/user-attachments/assets/c6ad0947-6c5b-4b3f-bbf7-5a3c4aef396c"
    link: "Portfolio/projects/#BaBaBANGSheep"
    tags: ["C#", "Unity", "Mobile", "Android"]

  - title: "Mesh Slicing"
    description: "A 3rd Year Game Mechanics project where I built a mesh slicing system in C++."
    details: "Built runtime plane-mesh intersection algorithms to dynamically recalculate vertices, UV coordinates, and caps."
    image: "Assets/MeshCuttingOne.gif"
    link: "Portfolio/projects/#Mesh_Cutting"
    tags: ["C++", "Algorithms", "3D Geometry", "UE5"]

  - title: "AI Evolution Simulation"
    description: "An AI simulation where creatures mutate and adapt to survive by seeking food and water."
    details: "Utilizes genetic algorithms to pass traits down across generations based on survival efficiency and resource gathering."
    image: "Assets/AI_Mutation.gif"
    link: "Portfolio/projects/#AI_Mutation"
    tags: ["C#", "AI / Mutation", "Unity", "Simulation"]

game_jams:
  - title: "Blue"
    description: "A Game Jam project exploring mood and atmosphere through minimalist design."
    details: "Developed within a 48-hour deadline focusing on lighting, atmospheric audio, and minimalist player interactions."
    image: "https://github.com/user-attachments/assets/0e8de0a7-45ea-4af8-afe3-82b733398430"
    link: "Portfolio/projects/#GameJams"
    tags: ["C#", "Unity", "Game Jam"]

  - title: "The Reapers Garden"
    description: "“An endless wave survival game set in a Reaper’s garden.”"
    details: "Fast-paced wave survival mechanics featuring custom enemy AI paths, weapon upgrades, and score tracking."
    image: "https://github.com/user-attachments/assets/b0b8752e-ca1d-40f0-bad4-d977ccefe3e4"
    link: "Portfolio/projects/#GameJams"
    tags: ["C#", "Unity", "Game Jam"]

  - title: "Skuffed"
    description: "A fast-paced game with chaotic mechanics, playful energy, and controlling your opponents arms."
    details: "Local multiplayer game incorporating physics-based limb movement and ragdoll interactions."
    image: "https://github.com/user-attachments/assets/6a611d58-fec7-4d5f-9831-1fe0a31d31ba"
    link: "Portfolio/projects/#GameJams"
    tags: ["C#", "Unity", "Co-op"]

  - title: "Fire Breathing Space Corgi"
    description: "A whimsical jam game featuring a corgi with cosmic powers."
    details: "A 2D arcade shooter made for a weekend game jam featuring custom particle effects and floating physics."
    image: "Assets/Corgi.png"
    link: "Portfolio/projects/#GameJams"
    tags: ["C#", "Unity", "2D Arcade"]
---

<div style="text-align:center; padding:1.5em 0; color:#004466;">
  <h1 style="font-size:2em; margin-bottom:0.3em;">Hi, I'm Alex</h1>
  <p style="font-size:1em; max-width:450px; margin:auto;">
    Games Programmer • Dare Academy Finalist (2025) • 4th Year at Abertay University
  </p>
</div>

<hr style="all: unset; display: block; height: 6px; background-color: #00aaff; margin: 2em 0;">

## On Going Projects

{% for project in page.ongoing %}
<div style="display:flex; align-items:flex-start; gap:1em; margin-bottom:1.5em; padding:0.8em; border:2px solid #00aaff; border-radius:12px; background:transparent; color:#004466;">
  <img src="{% if project.image contains '://' %}{{ project.image }}{% else %}{{ project.image | relative_url }}{% endif %}" alt="{{ project.title }}" style="width:160px; height:auto; border-radius:8px;">
  
  <div style="flex:1; text-align:left;">
    <h3 style="margin-top:0; margin-bottom:0.3em;">{{ project.title }}</h3>
    <p style="margin:0.5em 0;">{{ project.description }}</p>

    <!-- Tags -->
    <div style="display:flex; flex-wrap:wrap; gap:0.4em; margin-top:0.8em; margin-bottom:0.8em;">
      {% for tag in project.tags %}
        <span style="font-size:0.75em; background:rgba(0, 170, 255, 0.1); color:#00aaff; border:1px solid #00aaff; padding:0.2em 0.6em; border-radius:4px; font-weight:600;">{{ tag }}</span>
      {% endfor %}
    </div>

    <!-- Expandable Section -->
    <details style="margin-top:0.5em;">
      <summary style="display:inline-block; padding:0.4em 0.9em; background:#00aaff; color:#fff; border-radius:6px; font-weight:bold; cursor:pointer; user-select:none; font-size:0.9em;">
        See More
      </summary>
      <div style="margin-top:0.8em; padding:0.8em; background:rgba(0, 170, 255, 0.05); border-left:3px solid #00aaff; border-radius:4px;">
        <p style="margin:0 0 0.6em 0; font-size:0.95em;">{{ project.details }}</p>
        <a href="{{ project.link | relative_url }}" style="color:#00aaff; font-weight:bold; text-decoration:underline; font-size:0.9em;">
          View Full Project Page &rarr;
        </a>
      </div>
    </details>
  </div>
</div>
{% endfor %}

## Featured Projects

{% for project in page.featured %}
<div style="display:flex; align-items:flex-start; gap:1em; margin-bottom:1.5em; padding:0.8em; border:2px solid #00aaff; border-radius:12px; background:transparent; color:#004466;">
  <img src="{% if project.image contains '://' %}{{ project.image }}{% else %}{{ project.image | relative_url }}{% endif %}" alt="{{ project.title }}" style="width:160px; height:auto; border-radius:8px;">
  
  <div style="flex:1; text-align:left;">
    <h3 style="margin-top:0; margin-bottom:0.3em;">{{ project.title }}</h3>
    <p style="margin:0.5em 0;">{{ project.description }}</p>

    <!-- Tags -->
    <div style="display:flex; flex-wrap:wrap; gap:0.4em; margin-top:0.8em; margin-bottom:0.8em;">
      {% for tag in project.tags %}
        <span style="font-size:0.75em; background:rgba(0, 170, 255, 0.1); color:#00aaff; border:1px solid #00aaff; padding:0.2em 0.6em; border-radius:4px; font-weight:600;">{{ tag }}</span>
      {% endfor %}
    </div>

    <!-- Expandable Section -->
    <details style="margin-top:0.5em;">
      <summary style="display:inline-block; padding:0.4em 0.9em; background:#00aaff; color:#fff; border-radius:6px; font-weight:bold; cursor:pointer; user-select:none; font-size:0.9em;">
        See More
      </summary>
      <div style="margin-top:0.8em; padding:0.8em; background:rgba(0, 170, 255, 0.05); border-left:3px solid #00aaff; border-radius:4px;">
        <p style="margin:0 0 0.6em 0; font-size:0.95em;">{{ project.details }}</p>
        <a href="{{ project.link | relative_url }}" style="color:#00aaff; font-weight:bold; text-decoration:underline; font-size:0.9em;">
          View Full Project Page &rarr;
        </a>
      </div>
    </details>
  </div>
</div>
{% endfor %}

## Game Jam Projects

{% for project in page.game_jams %}
<div style="display:flex; align-items:flex-start; gap:1em; margin-bottom:1.5em; padding:0.8em; border:2px solid #00aaff; border-radius:12px; background:transparent; color:#004466;">
  <img src="{% if project.image contains '://' %}{{ project.image }}{% else %}{{ project.image | relative_url }}{% endif %}" alt="{{ project.title }}" style="width:160px; height:auto; border-radius:8px;">
  
  <div style="flex:1; text-align:left;">
    <h3 style="margin-top:0; margin-bottom:0.3em;">{{ project.title }}</h3>
    <p style="margin:0.5em 0;">{{ project.description }}</p>

    <!-- Tags -->
    <div style="display:flex; flex-wrap:wrap; gap:0.4em; margin-top:0.8em; margin-bottom:0.8em;">
      {% for tag in project.tags %}
        <span style="font-size:0.75em; background:rgba(0, 170, 255, 0.1); color:#00aaff; border:1px solid #00aaff; padding:0.2em 0.6em; border-radius:4px; font-weight:600;">{{ tag }}</span>
      {% endfor %}
    </div>

    <!-- Expandable Section -->
    <details style="margin-top:0.5em;">
      <summary style="display:inline-block; padding:0.4em 0.9em; background:#00aaff; color:#fff; border-radius:6px; font-weight:bold; cursor:pointer; user-select:none; font-size:0.9em;">
        See More
      </summary>
      <div style="margin-top:0.8em; padding:0.8em; background:rgba(0, 170, 255, 0.05); border-left:3px solid #00aaff; border-radius:4px;">
        <p style="margin:0 0 0.6em 0; font-size:0.95em;">{{ project.details }}</p>
        <a href="{{ project.link | relative_url }}" style="color:#00aaff; font-weight:bold; text-decoration:underline; font-size:0.9em;">
          View Full Project Page &rarr;
        </a>
      </div>
    </details>
  </div>
</div>
{% endfor %}

Explore more on the [Projects Page]({{ '/projects' | relative_url }}) or directly on itch.io:

- [Bong](https://alex-onions.itch.io/bong)  
- [Magnus's Library](https://alex-onions.itch.io/magnuss-libary)  
- [Maledictum Colori](https://alex-onions.itch.io/maledictum-colori)  
- [Clash Of The Roots](https://alex-onions.itch.io/clash-of-the-roots)  
- [Breadpocalypse](https://park66.itch.io/brotc)  
- [Paranormal Containment Protocol](https://park66.itch.io/paraconpro)
