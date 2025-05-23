# Somnia
![HighresScreenshot00005](https://github.com/user-attachments/assets/ad2f0d00-282d-448b-83bf-1c94f7a4d631)

**A Mental Health-Inspired 2.5D Platformer Game Demo**

## 🎮 Introduction
**Somnia** is a narrative-driven 2.5D platformer game that explores the connection between mental health and interactive storytelling. You play as a character who wakes up in a hospital with fragmented memories and must uncover the truth through puzzle-solving, environment interaction, and dialogue choices that shape your mental state.

---

## 🧠 Game Concept

### 🔍 Overview
Somnia combines:
- **3D environments** with a **2D side-scrolling perspective**
- A **branched dialogue system** influencing gameplay and narrative
- Mental health concepts reflected in gameplay mechanics, level design, and AI behavior

### 💡 Motivation
The game was born from a passion for gaming and the desire to tackle underrepresented themes—especially mental health—in a meaningful and immersive way. Inspired by games like *Inside*, *Limbo*, and *Little Nightmares*, Somnia aims to emotionally connect with players through symbolism and mechanics.

### 🎯 Objectives
- Integrate puzzle-solving, branching dialogues, and AI into a seamless player experience
- Create an emotionally immersive world reflecting depression, anxiety, and schizophrenia
- Deliver a technically sound and scalable experience, even at the demo phase

---

## 🧩 Problem & Solution

### ❓ Problem Statement
Representing mental health conditions in video games is complex. Somnia attempts this by letting player choices in dialogue influence mental states, which then dynamically affect:
- **Level design**
- **AI behavior**
- **Puzzle logic**

### ✅ Solution Overview
![Screenshot 2025-05-23 at 20-42-58 TV and Film Moodboard Presentation in Black and White Grey Minimalist Style - FaresNajjar-TahaArbas-CSIS290 pdf](https://github.com/user-attachments/assets/3ac54536-e11a-4e90-b3da-7358bac7dd5e)

#### 🌟 Key Features:
1. **Mental State-Driven Gameplay**  
   - Dialogue choices affect mental states  
   - Mental states modify game environment and behavior

2. **Branched Dialogue System**  
   - Meaningful choices with lasting consequences  
   - Impacts player psychology and world response

3. **AI Behavior (Planned)**  
   - Future versions will include ghost NPCs reflecting mental states

4. **Puzzle Mechanics**  
   - Integrated into level design and tied to mental states

5. **Environmental Storytelling**  
   - Lighting, atmosphere, and visuals adapt to psychological conditions
  
     ## 🎮 Images from the game 

![2512B2AA-6EBA-402E-8AF7-2D312AFF6703](https://github.com/user-attachments/assets/5e617e09-db6d-4366-8de7-a237245fa165)
![image](https://github.com/user-attachments/assets/38dfbc89-0a41-4c81-8b6c-f006aca02a0b)



---

## 🛠️ Technology Stack

### 🧑‍💻 Programming
- **C++**: Core performance and gameplay logic
- **Blueprints**: Visual scripting for quick iteration

### 🎮 Engine & Frameworks
- **Unreal Engine 4**
  - AI Behavior Trees
  - Actor-Component System
  - Animation State Machines
  - Niagara VFX
  - Level Streaming & Scalability System

### 🛠️ Tools
- **MakeHuman**: NPC creation
- **Visual Studio**: Development IDE
- **Blender**: Mesh editing & animation tweaking
- **Mixamo**: Rigging & animation
- **Pixabay**: Audio assets
- **FAB Marketplace**: Game assets
- **GitHub + GitLab**: Source code and asset version control

### 📚 APIs
- Unreal Engine C++ & Blueprint API References

---

## 🧠 System Design

### 🧠 Mental State Manager
- Central logic controller for mental state evaluation
- Handles save/load across levels, scoring, and dominant state detection
  ![Screenshot 2025-05-17 at 22-05-17 Online SVG Code Editor](https://github.com/user-attachments/assets/ae4fd710-9e7b-4a85-8618-f245270d527e)
![Screenshot 2025-05-17 at 21-53-58 ](https://github.com/user-attachments/assets/2c4d1eca-0572-4fcd-a98d-a3ebb3d93b45)


### 🧠 AI Behavior Trees
- Decision-making system using:
  - **Selector** nodes
  - **Sequence** nodes
  - **Tasks**, **Services**, and **Decorators**
![Screenshot 2025-05-17 at 15-24-16 AI Behavior Tree Architecture - Claude](https://github.com/user-attachments/assets/0c2f5955-9469-4639-8c38-8a526868fa75)


### 🧠 Branched Dialogue System
- Dialogue data stored using `FDialogueStructure`
- Temporary/in-game dialogue stored using `FDialogueLine`
 ![sequence-diagram](https://github.com/user-attachments/assets/12f9be78-6c62-4d8f-b07a-124f83883e9c)
![Screenshot 2025-05-17 at 22-27-07 Online SVG Code Editor](https://github.com/user-attachments/assets/37a0eccb-9ff0-441d-a40e-6d783b0841d6)



### 🗺️ Level Design & Optimization
![image](https://github.com/user-attachments/assets/5060db65-239a-4602-94eb-96a41f4deeb0)

- Divided into **3 major maps**, further split into sublevels
- **Level streaming** based on player position and view
- **Optimized rendering** to reduce overhead


### 📉 Scalability
- **LOD (Level of Detail)** models
- Graphics settings configurable by player
- Supports low-end PCs

### 🎞️ State Machine for Animations
- Smooth character animation transitions
- Responsive movement logic
  ![Screenshot 2025-05-17 at 23-12-49 Online SVG Code Editor](https://github.com/user-attachments/assets/a89ab879-39e9-4567-9c7a-2157b80d1035)
  

---

## ⚙️ Challenges

### 🧪 Technical
- Engine crashes, memory leaks
- Optimization
- Sparse documentation for UE4 C++

### 🧠 Non-Technical
- Learning Unreal Engine under time pressure
- Brainstorming and designing a deep concept
- Limited team size (2 developers)
- Managing scope and timeline

### 🛠️ Solutions
- Persistence
- Strong team collaboration
- AI tools to enhance learning and productivity
- A lot of coffee ☕️

---

## 🧠 Academic Contribution

### 👨‍🏫 Relevant Courses
- **Data Structures & Algorithms**: Mental state tracking
- **OOP**: Engine and system design
- **Software Analysis & Design**: Code/level planning
- **Computer Graphics**: Rendering logic & optimization

### 💡 Core Competencies Gained
- Game AI & Behavior Trees
- System Architecture
- Teamwork & Planning
- Storytelling in Games
- Optimization Techniques

---

## 🚧 Limitations & Future Plans

- The game is in **early demo phase**
- Full dynamic NPCs tied to mental states will be in the complete version
- Full release planned within a year
- The current version is for **feedback and quality assurance**
- Final game expected to launch on **Steam**

---
## 📽️ Demo Trailer (Soon)


---

Thank you for exploring Somnia. We hope to share more updates soon!


