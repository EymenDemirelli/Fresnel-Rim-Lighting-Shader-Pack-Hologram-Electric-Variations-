📌 Title

Fresnel Rim Lighting Shader Pack (Hologram + Electric Variations)

🧾 Description

This project presents a stylized Fresnel-based rim lighting shader system developed in Unity Shader Graph.

The shader is designed as a reusable and parameter-driven system, supporting multiple visual variations built on the same core logic. Currently, it includes two main effects: a hologram-style glow and an animated electric shock effect.

The goal is to demonstrate how a single shader foundation can be extended into different VFX styles through parameter control and simple modulation techniques.

🔧 Features
Fresnel-based rim lighting system
Two visual variations:
Hologram effect
Electric shock effect
Fully parameterized structure
Real-time control in material inspector
Reusable shader setup
⚙️ Parameters
Core Controls
Rim Power → Controls edge sharpness
Rim Intensity → Controls rim visibility
Base Color → Main color of the effect
Emission Strength → Overall glow intensity
Electric Variation Only
Pulse Speed → Animation speed
Pulse Intensity → Strength of flicker
🧠 Technical Overview

The shader is based on the Fresnel effect, where surface intensity increases at grazing view angles.

The rim mask is generated using the dot product between surface normals and the view direction, then shaped and amplified for stylized control.

For the electric variation, a time-based modulation is applied to the emission, creating a dynamic pulsing effect.

🎯 Purpose
Build a modular shader system from a single base
Explore Fresnel-based shading techniques
Extend static lighting into animated VFX
Create reusable stylized effects for games
🛠️ Setup / How to Use
Requirements
Unity (e.g. 2022.3 LTS)
URP or HDRP (Shader Graph required)
Installation
Download or clone the repository
Open the project in Unity Hub
Ensure the correct Render Pipeline is assigned
Locate the material using the shader
Adjust parameters in the Inspector
Usage
Use Rim parameters to control edge appearance
Switch between styles using emission + animation settings
Assign custom colors for different looks
⚠️ Notes
If material appears pink → pipeline is not set correctly
Ensure Shader Graph is supported in the project
Works best with emissive-enabled materials
🚀 Future Improvements
Additional variations (burn / dissolve / glitch)
Performance optimization (mobile focus)
Custom noise integration
Advanced animation controls
