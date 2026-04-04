Virtual Implementation Of Kalvari Class Submarine — An Immersive Submarine Training System

Step inside a Kalvari-class submarine and train through an interactive, spatial environment.

Overview
This is a virtual reality training platform that converts a submarine into a navigable, interactive learning system. Users can explore compartments, interact with systems, and perform procedural training with feedback and analytics.

Deliverables:
1. Navigable 3D Control Room Prototype
-Free-roam and guided walkthrough modes
-Equipment labels and tooltips
-Compartment orientation cues
-Interactive elements:
-Hatch interaction
-IPMS panel interaction
-Steering console

2. SOP Procedure Module
-Scenario: Diving Stations Sequence
-Step-guided checklist
-Go / No-Go validation
-Completion score

3. Multiplatform Build
-Windows standalone build
-VR headset (Meta Quest 2)
-Optional WebXR fallback

4. Trainee Analytics Dashboard
Tracks:
-Compartments visited
-Interactions performed
-SOP steps completed

5. Bonus (Planned)
-AI instructor avatar
-System identification tooltips
-AR overlay mode


Tech Stack:
-3D Modeling:Blender
-Engine:Unreal
-VR Framework:OpenXR / XR Toolkit
-Platforms:Windows, Meta Quest


Project Structure:
Kalvari-VR/
│
├── Assets/
│   ├── Models/
│   ├── Textures/
│   └── Materials/
│
├── Scenes/
│   ├── ControlRoom
│   └── Walkthrough
│
├── Scripts/
│   ├── Interaction/
│   ├── SOP_Module/
│   └── Analytics/
│
├── Builds/
│   ├── Windows/
│   └── VR/
│
├── Docs/
│   ├── Architecture.md
│   ├── SOP_Flow.md
│   └── Interaction_Design.md
│
├── Media/
│   ├── Screenshots/
│   └── DemoVideo/
│
└── README.md
