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
<img src="{{ '/Assets/Sword_Bp2.png' | relative_url }}"
     alt="Procedural Sword Generation Thumbnail"
     style="
       height:260px;
       width:200px;
       object-fit:cover;
       object-position:left;
       border-radius:12px;
       border:2px solid #00aaff;
     ">

  <div style="flex:1;">
    <p>
      My Honours Project explores procedural weapon generation, focusing on the creation of
      fully parametric swords built at runtime. The system constructs the blades using mathematical rules,
      shape grammars, and mesh‑generation algorithms. Afterwards the appropriate hilt, guards and pommels
      are attached.
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

<div style="padding:1em; border:2px solid #00aaff; border-radius:12px; margin-bottom:1.5em; color:#7fd3f0;">
  <h3 style="margin-top:0; color:#66c7eb;">Core Components</h3>
  <ul style="color:#7fd3f0;">
    <li><strong style="color:#66c7eb;">Parametric Blade Generator:</strong> Length, curvature, bevels, fuller depth, tip style.</li>
    <li><strong style="color:#66c7eb;">Mesh Construction:</strong> Vertex generation, triangle indexing, UV mapping.</li>
    <li><strong style="color:#66c7eb;">Interpolation:</strong> Curved Blade, Smooth Edges, Spline Curvature, Catmull-Rom.</li>
    <li><strong style="color:#66c7eb;">Style Profiles:</strong> “Elegant”, “Brutal”, “Fantasy”, “Historical”, etc.</li>
    <li><strong style="color:#66c7eb;">Textures/Shaders:</strong> “Rustic”, “Shiny”, “Chipped”, “Clean”, etc.</li>
    <li><strong style="color:#66c7eb;">Guard & Hilt Modules:</strong> Cross‑guards, T‑guards, curved guards, wrapped handles.</li>
    <li><strong style="color:#66c7eb;">Pommel Variants:</strong> Spheres, discs, spikes, geometric shapes.</li>
  </ul>
</div>

## 🧩 Generation Pipeline

### 1. Parameter Selection  
- Randomised or user‑defined  
- Style‑weighted distributions  
- Ensures coherent silhouettes  

### 2. Shape Construction  
- Blade spline generation  
- Cross‑section Addition  
- Guard/hilt/pommel Attachment  

### 3. Mesh Building  
- Vertex grid creation  
- Triangle indexing  
- Normal calculation  
- UV projection  

### 4. Post‑Processing  
- Edge sharpening  
- Decorative patterns  
- Material/Shader assignment  


### 5. Exporting/Saving
- Saving Sword
- Loading Sword
- Exporting Sword


## 🎮 2D Demonstration

<div style="display:flex; justify-content:center; gap:1.5em; margin:2em 0; flex-wrap:wrap;">

  <img src="{{ '/Assets/SwordDemo.gif' | relative_url }}"
       alt="Procedural Sword Generation Demo"
       style="width:45%; max-width:350px; border-radius:12px;">

  <img src="{{ '/Assets/Demo_Gif_3.gif' | relative_url }}"
       alt="Procedural Sword Generation Demo 2"
       style="width:45%; max-width:350px; border-radius:12px;">

</div>

<p style="text-align:center; color:#66c7eb; margin-top:0.5em;">
  Example swords generated entirely at runtime. (Prototype)
</p>

## Blade Generation - Steps For Creating The Base Blade

### 1. First the Blade is generated as a flat 2D mesh based on:
- A Spline based center lines
- Left and right edge profiles
- subdivded cross sections along the blade length

### 2. Blade surface normals are calculated using:
- The width Direction
- The Forward Direction
- Their cross product which ensures a consisted extrusion direction

### 3. The original 2D vertices are then offset based on half the blades thickness:
- This becomes the front face
- keeps the final mesh centered around its original plane

### 4. The back face is then created by:
- Duplicating all front face vertices
- Offsetting them backwards by the same half thickness
- Reversing the triangles so normals face outwards

### 5. The front and back faces both define the blades volume
- This can be used for calulating properties like weight and other stats 

### 6. The Side Wall are generated by:
-  Connecting corresponding edge veritces between front and back faces
-  Forming quads split into triangles
-  Fully Connecting the mesh

### 7. The final result is a 3D mesh with:
- Correct normals
- Uniform thickness
- No Gaps or Flippes Faces

### 8. Normals and tangents are recalculated to ensure:
- Proper Lighting
- Compatibility with Rendered Materials  


## Shapening the blade
### --- IN PROGRESS ---
</br>

## Creating the tip
### --- IN PROGRESS ---
</br>

## Creating the Shader
### --- IN PROGRESS ---

## Applying the Shader
### --- IN PROGRESS ---

## Finishing Touches
### --- IN PROGRESS ---

</br>




## ✅ Results & Evaluation

<div style="padding:1em; border:2px solid #00aaff; border-radius:12px;">
  <ul>
    <li>Successfully Generated 2D Blades based on Paramaters.</li>
    <li>Successfully added blade curvature, based on historical swords.</li>
    <li>Successfully created visually appealing 2D blade shape for swords.</li>
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
