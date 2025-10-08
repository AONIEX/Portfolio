---
layout: default
title: Projects
permalink: /Portfolio/projects/
---


<hr style="all: unset; display: block; height: 6px; background-color: #00aaff; margin: 2em 0;">

# Projects and Achievements

<div class="project-nav" style="display: flex; flex-wrap: wrap; gap: 0.5em; justify-content: center; margin-bottom: 1em;">


 <a href="#Dare_Academy" style="text-decoration: none;">
  <div class="project-button">
    <div class="project-text">
      <h5 style="margin: 0;">Dare Academy</h5>
    </div>
  </div>
</a>

 <a href="#Synaptic" style="text-decoration: none;">
  <div class="project-button">
    <div class="project-text">
      <h5 style="margin: 0;">Synaptic</h5>
    </div>
  </div>
</a>

 <a href="#Mesh_Cutting" style="text-decoration: none;">
  <div class="project-button">
    <div class="project-text">
      <h5 style="margin: 0;">Mesh Cutting</h5>
    </div>
  </div>
</a>

 <a href="#BaBaBANGSheep" style="text-decoration: none;">
  <div class="project-button">
    <div class="project-text">
      <h5 style="margin: 0;">BaBaBANG!Sheep</h5>
    </div>
  </div>
</a>

 <a href="#GameJams" style="text-decoration: none;">
  <div class="project-button">
    <div class="project-text">
      <h5 style="margin: 0;">Game Jams</h5>
    </div>
  </div>
</a>

  <!-- Add more buttons as needed -->
</div>


<hr style="all: unset; display: block; height: 6px; background-color: #00aaff; margin: 2em 0;">

<a id="Dare_Academy"></a>
## Dare Academy
<!-- content -->



### Dare Academy (Synaptic)
Dare Academy is a competetion hosted by Abertay University, where students can apply with a team of up to 8 people. Only 6 teams can become finalists and mine was one of them (The Bonny Bandits). As a team we pitched a university project for this competition and then developed it into a working a playable game, showcasing at events at locatsions like the DCA (Dundee Contemporary Arts) and Water's Edge (Dundee) as well as talking to industry experts.

![Team Photo](Assets/TheTeam.jpg)


#### This oppurnity allowed me to develope my communication, teambuilding, programming, showcasing, and pitching skills. 
 - The ability to collabarate and talk to industry experts helped increase my programming and problem solving skills.
 - The oppurtunity to showcase at the DCA and Water edge helped me  massively improve my communication, showcasing and pitching skills.
 - Working closely with the team of 8 has helped me with team building as well as learning how to collabarate with different departments effectively.
 - The oppurtunity to showcase the game, helped me focus on fixing bugs, polishing mechanics and making features fun and accessible.

![Team Photo](Assets/Event.jpg)


#### Core Focuses During Dare Academy Hot housing (Development Period)
- UI:
  - Polished and more settings were added (Aim Assist, Motion Sickness and other accessabilty settings).
  - Pause menu made to pause the game
  - Controller support
  - Selected button highlighting.
- Controller Support:
  - Huge focus of mine during the second half of development, researching the best way to implement it
  - Making sure the mechanics and UI worked smoothly on controller
  - Changing any features needed for smoother gameplay wiht controller whilst keeping it similar to the mouse and keyboard feel
- Aim Assist
  - This was a key accessability feature added for people with slower reaction times, as well as making playing with a controller easier. Using ray tracing to know when to apply aim assist
- Motion Sickness Mode
  - This was added to remove/reduce the visual effects, camera shake and anything that would make the player uncomftable or cause them to feel nautious.
- Polishing Weapon Mechanics:
  - the weapons were play tested countless times to make sure they felt smooth and good to use.
- Animations connections for Ammo Display and Weapon animations:
  - worked closely with the animation to line up the animation timings and for them to work for the correct weapons
- Testing
  - Mechanics Testing
  - Build Testing
  - Checking that all targets are shootable   



<hr style="all: unset; display: block; height: 6px; background-color: #00aaff; margin: 2em 0;">

<a id="Synaptic"></a>
## Synaptic
<!-- content -->

### Synaptic (Before Dare Academy)
Synaptic is one of my biggest projects and is a game made for my 3rd year professional project class, which was then taken forward to Abertay's Dare Academy. This game was made as with a team of 8 and my role was the Weapons, UI, Interactions and Accesability Programmer. This project has helped with my team building skills, helping me stay in contact with team members and stick to deadlines. I also learned alot about the collabrative side of programming and how important it is to keep in contact with out professions to keep work flowing. For example keeping up to date with the animation team so we can link the animations to the code on time.
<br/>
<br/>

### Extra Information
- [Synaptic's Itch.io Page](https://bonny-bandits.itch.io/synaptic)
- Game Engine: Unreal Engine 5
- Team Project
- Language: C++

 
<br/>

![Synaptic Gif One](Assets/SynapticOne.gif)


#### Core Focuses During Development
- Weapon Mechanics & Bullet Behaviours
  - Finger guns
    - A classic video game gun, fires a bullet as expected
    - Created bullet drop for the bullet drop so the weapon felt like it needed some skill  
  - Scissors
    - The weapon focuses on letting the player cut targets in half before destorying them
    - This included working with changing and cutting meshes in half, creating a new mesh/object based on teh new half with its own collisions and physics  
  - Fist/Chatter Gun
    - This weapon creates a gravitational pull which sucks in nearby targets destroying them upon impacts, and causing them to have a zero gravity effect
    - This included working with physics to let the targets float and get pulled in as wanted, alot of testing and fiddling was needed to get this effect to feel right.
- Player Movement
  - Basic Player Movement (W,A,S,D) or (Analog Stick) Based walking
  - Head Bobbing and Camera Shaking based on shooting, movement and interactions
- Sanity and Calming
  - Created Sanity bar to keep track of players sanity
  - Connected and ditsvisual effects to sanity to allow for correct display
  - Created calming mechanics to increase players sanity
- Interactions
  - Hub interactions with unique functions
- Focusing on object/locations
  - Camera focuses/looks at set targets or locations
  - Used for tutorials to allow information to be showed based on correct enemies
  - Used for opening and final cutscenes

![Synaptic Gif Two](Assets/SynapticTwo.gif)
   
- UI and Settings
  - Main Menu, End Screen
    - Connections to settings, ability to start and exit game
  - Settings
    - Ability to turn on/off subtitles, audio, change specific volumes
    - Communication on needed settings
  - In Game Pause Menu
    - Ability to Pause game, Access settings, Tutorial, Exit game, Go to Main Menu
- Testing and Building
  -  Testing the game looking for bugs and errors
  -  Fixing Errors and bugs
  -  Build Testing and fixing, passing on information to producer
- Animation Connections
  - Working with Animatior to connect animations to weapons and calming mechanics
  - Created a system for fingers ammo display
  - Discussing and fixing animation timing problems   

<hr style="all: unset; display: block; height: 6px; background-color: #00aaff; margin: 2em 0;">

<a id="Mesh_Cutting"></a>
## Mesh Cutting

### Game Mechanics Programming Mesh Cutting (3rd Year University Project)


The project was made for Game Mechanics Programming (3rd Year Class), where i had to make a unique game mechanic in Unreal Engine 5 using C++ with minimal blueprint use. For this i decided to make a mesh cutting "Weapon" which allowed the player to cut out parts of a mesh, before being able to grab them and then return them to their original position if wanted.
<br/>

![Mesh Cutting Gif One](Assets/MeshCuttingOne.gif)


### My Focus
My Core Focus in this project was the ability to edit/cut the mesh during run time, slitting in two or more pieces, each with their own physics and collisions. I developed my skills on ray tracing using it to make the the mesh was cut in the correct postions. I originally it so the objects were cut in half then decided to go for a more complex rectangular shape. 

### Below are the main features used and what i learned
- Ray Tracing
  - Used figure out the position that the player wanted to cut the mesh, using it to calculate the start and end point of the chunk the player wanted cut
  - This was also used to figure out if the mesh was cutable or not
  - Used to pick up and move objects around
- Procedural Mesh
  - I learned alot about the performance needs of editing procedural meshes at run time and to take then into account, not letting the player cut models that are too complex
  - I learned how to deform and merge meshes
  - I learned how to have a procedural mesh copy the componentes of another mesh
  - I learned how to find the centre of the cut mesh as it would normally be based on the old mesh
- Physics and collisons 
  - I learned how un predictable physics can be when slicing meshes and changing collisions, as well as how to erase or minimise the chaotic affects
  - I learned how to apply physics and collisions based on the new mesh when cut and the new object/mesh made

### How i would extend this project
If i had more time i would like would advance this project by letting the player cut out more complext shapes, or even custom shapes with the player choosing the shape. I would also fix the small movement issues with the grabbing of some fo the meshes as well as the returing and merging of the mesh, though these are purely for visuals and woudln't affect gameplay use.
  
### Extra Information
- Game Engine: Unreal Engine 5
- Solo Project
- Language: C++
- Ray Tracing
- Procedural Mesh Cutting/Deformation/Creation

<br/>

![Mesh Cutting Gif Two](Assets/MeshCuttingTwo.gif)
<br/>
[Mesh Cutting Git Page](https://github.com/AONIEX/MeshCuttingWORKING)
<br/>
[Mesh Cutting Video Demonstration](https://www.youtube.com/watch?v=rBjXFgnGRYU)



<hr style="all: unset; display: block; height: 6px; background-color: #00aaff; margin: 2em 0;">

<a id="BaBaBANGSheep"></a>
## Ba Ba BANG! Sheep
 
Ba Ba BANG! Sheep is a first year project which i have grown and worked on when not working each summer. It started as a SFML game for PC but i quickly moved it over to Unity (C#) and made the game work for both PC and Mobile, with the game currently having a downloadable android version. The game consists of a infinte procedurally generated level with platforms and enemies constantly spawning and changing as the player tries to move up and get a new high score. 

![Ba Ba BANG Sheep Gif One](Assets/BangOne.gif)


### Core Focuses
My core focus with Ba Ba BANG! Sheep has always been to expand my knowledge of Unity (C#), Procedural Generation, Ogranisation and Mobile Development. This is mainly due to not doing much Unity or Mobile Development in University, and wanting to keep up to date with my procedural generation and ability to keep a project organised and easy to come back to. I also found that it is good to have a project to come back to each summer and see how my skills have changed, as i notice a huge difference each year.

This project taught me alot about prefabs, inheritance, parent classes and how to use them properly to stop myself from re writing code where avoidable. It has also shown me the imporatance of object management and performance, due to working with an "infintely" generated level.

I have also been able to learn about mobile development and the important aspects to keep in mind when working on developing a mobile game, that are different to your usual game on a pc.
<br/>

![Ba Ba BANG Sheep Gif Two](Assets/BangTwo.gif)

### What i've learned
- Mobile Development
  - Performance is alot more important
  - Layout needs to be thought out, Unique Aspect Ratios for each phone and the game should be scaled correctly
  - Less controls is usually better
  - Touch Controls and its unique challenges
- Unity
  - Expanded knowledge on unity's tools, C#, Scripting, Prefabs, Inheritance
  - Expanded knowledge on UI, UI proramming, Animation, Linking Animation to code
  - Massively Improved my ability to call sounds correctly through code, and stop bugs like sound overlapping or being called repeatedly
- Procedural Level Generation
  - How to generate a constantly changing infinte level
  - Having unique areas and enviroments
  - Generating the level whilst keep player progression and enemies in mind
  - Making sure the level is visually pleasing and unique
  - Having  enemies and pick ups spawn based on the generated level
- Inheritance used for Enemies (Base Class and Parent Class)
  - Learned the importance of inheritance and not needing to repeat code
  - Learned about the advantages of base classes like being able to edit core functions of all enemies at ones
  - Learned to make different types of enemies each of which inherit from a class that inherits from the base class
  - Fixed issues due to inheritance due to original not understanding
- Performance
  - Re-use objects, dont delete and re-create
  - Dont use too many objects
  - Only render what the player should be able to see, not what isnt in the players line of sight
- Testing
  - Testing for Mobile and PC
  - Error and bug handling
  - The Importance of regular testing 

![Ba Ba BANG Sheep Gif One](Assets/RainScreenShot.png)

### Extra Information
- Game Engine: Unity
- Solo Project
- Language: C#
- Mobile and PC Development
<br/>
[Ba Ba BANG Sheep Itch.io Page](https://alex-onions.itch.io/ba-ba-bang-sheep)
<br/>


<hr style="all: unset; display: block; height: 6px; background-color: #00aaff; margin: 2em 0;">

<a id="GameJams"></a>
## Game Jams
Before and during at university i have taken part in multiple game jams to refresh and improve my knowledge. The main thing i try to do every game jam is make each game unique, whether thats a new genre or different core mechanics as i believe this allows me to learn more in such a short amount of time.

## Blue

<img width="315" height="250" alt="Blue" src="https://github.com/user-attachments/assets/0e8de0a7-45ea-4af8-afe3-82b733398430" />

<br/>


  - Blue was made for the Speed Jam #5 with a themes Speed Running and ASCEND. For this Project i wanted to work with lighting and ambience to give the game a nice feel and look whilst having minimal controls (Just a drag and click). I did this game alone, so worked on every aspect, and wanted to take a short break from coding to learn about the other aspects of game development as i believe it is important to understand what each department ahs to deal with

### Extra Information
  -  Solo Project
  - Game Engine: Unity
  - Language: C#
  - [Blue Itch.io Page](https://alex-onions.itch.io/blue)



 ## The Reapers Garden

<img width="315" height="250" alt="Reap" src="https://github.com/user-attachments/assets/b0b8752e-ca1d-40f0-bad4-d977ccefe3e4" /> 

<br/>

  - This was one of my first game jam games with a theme of 2 colours, no shades just black and white. I believe i learned the fundamentals of Unity for this project, when making this wave based game. I also chose to add a unique mechanics of collecting souls for the reaper to regrow their garden. This was quite a simple project but also allows me to show how far my skills have come.


### Extra Information
  - One of my First Game Jams
  - Solo Project
  - Game Engine: Unity
  - Language: C#
  - [The Reapers Garden Itch.io Page](https://alex-onions.itch.io/the-reapers-garden)

 ## Skuffed

<img width="315" height="250" alt="Skuffed" src="https://github.com/user-attachments/assets/6a611d58-fec7-4d5f-9831-1fe0a31d31ba" />

<br/>

  - This project was a team project i did in my 3rd year of university and i took it on myself to have a team of 3rd years so i can see how it is to help people learn and work wiwth less experience people. Even though i was working with lesss experienced people i still wanted to do something unique, so we decided to do a two player rigid body physics game, where you would control your oppents arms and your legs whilst trying to race towards a finish line and screw up your enemy.


### Extra Information
  - Team Project
  - Game Engine: Unity
  - Language: C#
  - [Skuffed Itch.io Page](https://alex-onions.itch.io/skuffed)
    

 ## Fire Breathing Space Corgi


 ![Fire Breathing Space Corgi](Assets/Corgi.png)

 <br/> 

  - This project was one of my first team projects in a game jam and was a big learning curve, figuring out how to learn with artists, level designers and audio designers. I focused on the core movements for the player and the AI for the enemies within the game, giving each of them unique mechanics, attacks and movement. For this i focused on state machines allowing an enemy to move between states based on if the enemy is close, what attack it wants to use and if it dies. I also made sure to re use this state machine for each enemy, making sure to re use the states that can re used.
   
 
   - Team Project
  - Game Engine: Unity
  - Language: C#
  - [Fire Breathing Space Corgi Itch.io Page](https://alex-onions.itch.io/fire-breathing-space-corgi)


 
 ## More Game Jam Games
  - [Bong](https://alex-onions.itch.io/bong)
  - [Fire Breathing Space Corgi](https://alex-onions.itch.io/fire-breathing-space-corgi)
  - [Magnus's Libary](https://alex-onions.itch.io/magnuss-libary)
  - [Maledictum Colori](https://alex-onions.itch.io/maledictum-colori)
  - [Clash Of The Roots](https://alex-onions.itch.io/clash-of-the-roots)
  - [Breadpocalypse](https://park66.itch.io/brotc)
  - [Paranormal Containmetn Protocl](https://park66.itch.io/paraconpro) 
