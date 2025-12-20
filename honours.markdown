---
layout: default
title: Projects
permalink: /Portfolio/honours/
---

<div style="text-align:center; padding:1.5em 0; color:#004466;">
  <h1 style="font-size:2em; margin-bottom:0.3em;">Honours Project</h1>
  <p style="font-size:1em; max-width:600px; margin:auto;">
    Procedural Sword Generation • Runtime Mesh Construction • Parametric Geometry
  </p>
</div>

<hr style="all: unset; display: block; height: 6px; background-color: #00aaff; margin: 2em 0;">


## 🗡️ Project Overview

<div style="display:flex; gap:1.5em; align-items:flex-start; margin-bottom:1.5em;">
  <img src="/Assets/SwordGenThumbnail.png"
       alt="Procedural Sword Generation Thumbnail"
       style="width:220px; height:auto; border-radius:12px; border:2px solid #00aaff;">
  <div style="flex:1;">
    <p>
      My Honours Project explores procedural weapon generation, focusing on the creation of
      fully parametric swords built at runtime. The system constructs blades, guards, hilts,
      and pommels using mathematical rules, shape grammars, and mesh‑generation algorithms.
    </p>
    <p>
      The goal is to create a flexible, extensible tool capable of producing thousands of
      unique, stylistically coherent weapons for games.
    </p>
  </div>
</div>


## 🎯 Research Motivation

<p style="max-width:750px;">
  Procedural content generation allows developers to create large quantities of unique assets
  without manually modelling each one. While PCG is common for terrain and levels, weapon
  generation remains under‑explored. My research investigates how parametric geometry,
  silhouette control, and modular design can be combined to generate swords that are both
  visually appealing and structurally believable.
</p>


## 🏗️ System Architecture

<div style="padding:1em; border:2px solid #00aaff; border-radius:12px; margin-bottom:1.5em;">
  <h3 style="margin-top:0;">Core Components</h3>
  <ul>
    <li><strong>Parametric Blade Generator:</strong> Length, curvature, bevels, fuller depth, tip style.</li>
    <li><strong>Guard & Hilt Modules:</strong> Cross‑guards, T‑guards, curved guards, wrapped handles.</li>
    <li><strong>Pommel Variants:</strong> Spheres, discs, spikes, geometric shapes.</li>
    <li><strong>Mesh Construction:</strong> Vertex generation, triangle indexing, UV mapping.</li>
    <li><strong>Style Profiles:</strong> “Elegant”, “Brutal”, “Fantasy”, “Historical”, etc.</li>
  </ul>
</div>


## 🧩 Generation Pipeline

### 1. Parameter Selection  
- Randomised or user‑defined  
- Style‑weighted distributions  
- Ensures coherent silhouettes  

### 2. Shape Construction  
- Blade spline generation  
- Cross‑section extrusion  
- Guard/hilt/pommel assembly  

### 3. Mesh Building  
- Vertex grid creation  
- Triangle indexing  
- Normal calculation  
- UV projection  

### 4. Post‑Processing  
- Edge sharpening  
- Decorative patterns  
- Material assignment  


## 🎮 Demonstration

<div style="text-align:center; margin:2em 0;">
  <img src="/Assets/SwordGenDemo.gif"
       alt="Procedural Sword Generation Demo"
       style="width:80%; max-width:700px; border-radius:12px; border:2px solid #00aaff;">
  <p style="color:#004466; margin-top:0.5em;">Example swords generated entirely at runtime.</p>
</div>


## ✅ Results & Evaluation

<div style="padding:1em; border:2px solid #00aaff; border-radius:12px;">
  <ul>
    <li>Still to be Evaluated as its an ongoing project</li>
  </ul>
</div>


## 🛠️ Tools & Technologies

- C#
- Unity
- Shadergraph
- In engine degugging tools


## 📥 Downloads & Links

- GitHub Repository: *Add link here*  
- Technical Report (PDF): *Add link here*  
- Demo Build: *Add link here*  


## 📚 References

- Relevant geometry and mesh‑generation literature.
