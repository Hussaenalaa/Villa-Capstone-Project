Villa Capstone Project — Unity 6.2 VR
Author: Hussaen Alaa
Instructor: Eng. Hatem Heshmat
Course: Professional 3D & VR Designer — Module 1
Date: October 2025

🎯 Project Overview
This project presents a VR environment and gameplay prototype developed as part of the Capstone Project for the Professional 3D & VR Designer course.

The experience is set in a villa’s backyard and basketball court, where players can explore, teleport, and interact with objects in a realistic outdoor space. The project demonstrates essential VR interaction systems designed for Meta Quest 2/3, built using Unity 6.2 LTS and the Meta XR All-in-One SDK (v65).

🧱 Implemented Features
✅ Player locomotion (continuous & snap turning)
✅ Hand grabbing and object manipulation
✅ Ray interactor with UI canvas support
✅ Realistic lighting and skybox setup
✅ Optimized performance for Quest 2 & Quest 3

🛠️ Tools & Packages Used

Tool / Package	Version	Purpose
Unity	6.2 LTS	Game engine
Meta XR All-in-One SDK	v65	VR input, teleportation, grab system
XR Interaction Toolkit	3.2.1	Extended VR interactions
URP (Universal Render Pipeline)	Default	Rendering & lighting
Shader Graph	—	Custom materials
Visual Studio	2022	C# scripting

📁 Project Structure

Assets/
├── Prefabs/
│   ├── PFB_Building_Full.prefab
│   ├── PlayerFPS.prefab
│   ├── Room.prefab
│
├── Scenes/
│   └── AmericanHome_Backyard.unity
│
├── Scripts/
│   ├── HoopTrigger.cs
│   ├── LightSwitchController.cs
│   └── ScoreManager.cs
│
└── Tools/
    ├── Door_2.05x0.9.prefab
    ├── Human_1.75m.prefab
    ├── Ruler_1m.prefab
    ├── XR Origin Hands (XR Rig).prefab
    └── TutorialInfo.meta
