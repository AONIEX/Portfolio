---
layout: default
title: Home
tags: ["C++", "C#", "Unity", "UE5"]

ongoing:
  - title: "Honours Project"
    description: "3D Sword Procedural Generation creating historically accurate and visually appealing weapons."
    details: "Exploration of procedural generation algorithms in real time to generate historically accurate blade profiles, crossguards, grips, and hilts in 3D."
    image: "Assets/sword2.png"
    link: "Portfolio/honours/"
    tags: ["C++", "Procedural Generation", "Unity", "3D Graphics"]

featured:
  - title: "Synaptic (Dare Academy Finalist)"
    description: "A 3rd-year team project in Unreal Engine 5, selected as a finalist for Abertay's Dare Academy."
    details: "As Weapons, UI & Accessibility Programmer, implemented custom C++ weapon mechanics (finger guns, mesh-slicing scissors, chatter gravity gun), UI, aim assist, motion sickness mode, full controller support, and animation systems."
    image: "https://github.com/user-attachments/assets/a12b8fc3-fe75-453e-8ef8-0454fba62356"
    link: "Portfolio/projects/#Dare_Academy"
    tags: ["C++", "Blueprints", "UE5", "Dare Academy", "Group Project"]

  - title: "Ba Ba BANG! Sheep"
    description: "An infinite procedural arcade platformer built in Unity (C#) for Mobile and PC."
    details: "Features an infinitely generated procedural level, mobile touch controls, aspect ratio scaling, object pooling, and parent/child inheritance structures for enemy behaviors."
    image: "https://github.com/user-attachments/assets/c6ad0947-6c5b-4b3f-bbf7-5a3c4aef396c"
    link: "Portfolio/projects/#BaBaBANGSheep"
    tags: ["C#", "Unity", "Mobile", "Android", "Procedural Generation"]

  - title: "Mesh Cutting"
    description: "A 3rd-year C++ project in Unreal Engine 5 focused on runtime procedural mesh cutting."
    details: "Uses ray tracing to calculate cut locations and dynamically slice procedural meshes into separate chunks at runtime, recalculating collision bounds, physics, and center of mass for each slice."
    image: "Assets/MeshCuttingOne.gif"
    link: "Portfolio/projects/#Mesh_Cutting"
    tags: ["C++", "UE5", "Ray Tracing", "Procedural Mesh"]

  - title: "AI Evolution Simulation"
    description: "A Unity (C#) simulation using Genetic Algorithms where creatures mutate and evolve to survive."
    details: "Implements crossover, mutation, and fitness scoring based on hunger/thirst. Includes custom UI sliders for population/food parameters and outputs survival data to text files for performance logging."
    image: "Assets/AI_Mutation.gif"
    link: "Portfolio/projects/#AI_Mutation"
    tags: ["C#", "Unity", "AI / Genetic Algorithms", "Simulation"]

game_jams:
  - title: "Blue"
    description: "A Speed Jam #5 project focusing on lighting, atmosphere, and minimal drag-and-click controls."
    details: "Created solo for Speed Jam #5. Focused on dynamic lighting, ambience, and simplified single-input controls to explore atmospheric visuals and audio design."
    image: "https://github.com/user-attachments/assets/0e8de0a7-45ea-4af8-afe3-82b733398430"
    link: "Portfolio/projects/#GameJams"
    tags: ["C#", "Unity", "Game Jam", "Solo"]

  - title: "The Reapers Garden"
    description: "A 2-color black & white wave survival game built in Unity (C#)."
    details: "A strict 2-color wave survival game where players collect souls to regrow the Reaper's garden while battling escalating waves of enemies."
    image: "https://github.com/user-attachments/assets/b0b8752e-ca1d-40f0-bad4-d977ccefe3e4"
    link: "Portfolio/projects/#GameJams"
    tags: ["C#", "Unity", "Game Jam", "Solo"]

  - title: "Skuffed"
    description: "A 2-player local physics game where players control their opponent's arms and their own legs."
    details: "Developed during 3rd year in a team mentoring 1st-year students. Utilizes Unity rigid-body physics to create chaotic limb controls and ragdoll racing mechanics."
    image: "https://github.com/user-attachments/assets/6a611d58-fec7-4d5f-9831-1fe0a31d31ba"
    link: "Portfolio/projects/#GameJams"
    tags: ["C#", "Unity", "Co-op", "Physics"]

  - title: "Fire Breathing Space Corgi"
    description: "A team game jam project featuring state-machine-driven enemy AI."
    details: "Focused on core player movement and flexible finite state machines for enemy AI, enabling dynamic state transitions between movement, multi-type attacks, and death."
    image: "Assets/Corgi.png"
    link: "Portfolio/projects/#GameJams"
    tags: ["C#", "Unity", "Game Jam", "AI State Machine"]
---

<div style="text-align:center; padding:1.5em 0; color:#004466;">
  <h1 style="font-size:2em; margin-bottom:0.3em;">Hi, I'm Alex</h1>
  <p style="font-size:1em; max-width:450px; margin:auto;">
    Games Programmer • Dare Academy Finalist • 4th Year at Abertay University
  </p>
</div>

<hr style="all: unset; display: block; height: 6px; background-color: #00aaff; margin: 2em 0;">

## Ongoing Projects

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

Explore more on the [Projects Page]({{ '/Portfolio/projects/' | relative_url }}) or directly on itch.io:

- [Bong](https://alex-onions.itch.io/bong)  
- [Magnus's Library](https://alex-onions.itch.io/magnuss-libary)  
- [Maledictum Colori](https://alex-onions.itch.io/maledictum-colori)  
- [Clash Of The Roots](https://alex-onions.itch.io/clash-of-the-roots)  
- [Breadpocalypse](https://park66.itch.io/brotc)  
- [Paranormal Containment Protocol](https://park66.itch.io/paraconpro)
