🏠 Villa Capstone Project — Unity 6.2 VR

Author: Hussaen Aladdin
Instructor: Eng. Hatem Heshmat
Course: Professional 3D & VR Designer — Module 1
Date: October 2025

🎯 Project Overview

This Unity project showcases a VR environment and gameplay prototype created as part of the Capstone Project for the Professional 3D & VR Designer course.

The experience takes place in a villa’s backyard and basketball court, where players can explore, teleport, and interact with various objects in a realistic outdoor setting.

It demonstrates core VR interaction systems designed for Meta Quest 2/3, built using Unity 6.2 LTS and the Meta XR All-in-One SDK (v65).

🧱 Features

✅ Player locomotion (continuous + snap turn)

✅ Hand grabbing and object manipulation

✅ Ray interactor with UI canvas support

✅ Realistic lighting and skybox setup

✅ Optimized performance for Quest 2/3

## 🛠️ Tools & Packages Used  

| Tool / Package | Version | Purpose |
|----------------|----------|----------|
| Unity | 6.2 LTS | Game engine |
| Meta XR All-in-One SDK | v65 | VR input, teleportation, grab system |
| XR Interaction Toolkit | 3.2.1 | Extended VR interactions |
| URP (Universal Render Pipeline) | Default | Rendering & lighting |
| Shader Graph | — | Custom materials |
| Visual Studio | 2022 | C# scripting |

---

## 📁 Project Structure  

```bash
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

🧩 Platform & Compatibility

VR Headsets: Meta Quest 2 / Quest 3

Unity Version: 6.2 LTS

Rendering Pipeline: Universal Render Pipeline (URP)

🚀 How to Run

Open the project in Unity 6.2 LTS.

Ensure Meta XR SDK v65 and XR Interaction Toolkit are installed.

Open the scene:

Assets/Scenes/AmericanHome_Backyard.unity


Connect your Meta Quest 2/3 via Link or Air Link.

Press ▶️ Play to test the VR environment.
