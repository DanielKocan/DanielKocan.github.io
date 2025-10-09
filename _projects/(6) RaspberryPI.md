---
name: Raspberry Pi 3D Runner
tools: [C++, 3D, OpenGL, RaspberryPI]
image: /assets/projects/RaspberryPI3DPitfall/main.gif
description: I developed a 3D runner game on Raspberry Pi using C++, OpenGL for rendering and Bullet Physics.
---

# 🍓 Raspberry Pi 3D Runner
For this project, I developed a 3D runner game on Raspberry Pi, inspired by the classic Pitfall!, using C++, OpenGL for rendering, and Bullet Physics for realistic simulation.
This was a hardware-constrained project, so I had to optimize performance carefully.

![preview](../assets/projects/RaspberryPI3DPitfall/main.gif)

# ✨ Core Features I Built
### Physics-Driven World

* Set up a full Bullet physics world, populating it with rigid bodies and managing physical interactions.
* Created accurate collision detection and response systems.

### Rendering Pipeline

* Integrated OpenGL shaders, camera systems, and lighting to display the game world.
* Extracted physics data from Bullet and used it to render debug and gameplay visuals.

![preview](../assets/projects/RaspberryPI3DPitfall/image8.png)

### Custom Models & World

* Loaded and displayed OBJ models, turning them into active physics shapes.
* Built a tile-based map system to lay out the runner’s environment.

![preview](../assets/projects/RaspberryPI3DPitfall/image158.png)
![preview](../assets/projects/RaspberryPI3DPitfall/image157.png)

### Player & Enemies

* Implemented player controls with applied physics forces, carefully tuning for responsive gameplay.
* Created a system of enemies using object-oriented programming, supporting multiple NPCs.

### UI & Menus

* Added in-game menus.
* Used Dear ImGui for real-time debug information and output.

### Final Touches

* Polished the game with sound integration, shader effects, and optimized configurations for Raspberry Pi hardware limits.

![preview](../assets/projects/RaspberryPI3DPitfall/gameplay.gif)

# 💡 What I Learned
This project gave me hands-on experience with:

* Low-level graphics programming using OpenGL
* Integrating physics libraries like Bullet into custom project
* Managing hardware constraints (Raspberry Pi)
* Designing gameplay systems tightly connected to physics
* Building interactive UIs and debug tools

It was an excellent exercise in combining engine-level development with gameplay design on embedded systems.



<p class="text-center">
{% include elements/button.html link="https://danielkocan.github.io/projects/" text="Go Back" %}
</p>

![BUAS](../assets/Logo_BUas_RGB.png)