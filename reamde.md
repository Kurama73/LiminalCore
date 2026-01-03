# LIMINAL CORE

> *"If you're not careful and you noclip out of reality in the wrong areas, you'll end up here."*

**LiminalCore** is a high-fidelity psychological horror framework built on **Unreal Engine 5.7**. It focuses on procedural non-Euclidean geometry, photorealistic lighting, and a tension-based AI Director, eschewing traditional combat for pure atmospheric dread.

---

## 🌑 The Concept

Inspired by the "Backrooms" lore and the visual style of Kane Pixels, this project explores the concept of **Liminal Spaces**.
* **Genre:** Psychological Horror / Walking Simulator.
* **Core Loop:** Exploration of a dynamically generating labyrinth that shifts behind the player's back.
* **Objective:** Survive the isolation. No weapons. No fighting. Only observation and flight.

## 🛠 Tech Stack

Designed for high-end hardware with a focus on cutting-edge rendering features.

* **Engine:** Unreal Engine 5.7+
* **Language:** Blueprints (Logic) / C++ (Performance critical algorithms).
* **Rendering:**
    * **Lumen:** Real-time Global Illumination & Reflections.
    * **Nanite:** Virtualized Geometry for cinematic quality assets.
    * **Hardware Raytracing:** Accurate shadows and translucency.
* **Assets:** Quixel Megascans ecosystem (No custom modeling).

## ⚙️ Key Systems

### 1. The Director (AI)
A logical layer that tracks player stress, gaze direction, and pacing. It does not spawn enemies to fight, but manipulates the environment (lights, sounds, door states) to maximize tension based on the player's lack of vision.

### 2. Wave Function Collapse (Lite)
A constraint-based procedural generation system using **Level Instances**.
* Rooms generate asynchronously.
* Seamless "out-of-sight" tile swapping to create infinite loops and non-Euclidean pathways.

### 3. VHS Bodycam Simulation
Physically based post-processing chain including:
* Chromatic Aberration.
* Lens Distortion.
* Grain & Rolling Shutter simulation.

---

## 📦 Setup & Installation

**Prerequisites:**
* Unreal Engine 5.7
* Git with **LFS (Large File Storage)** installed.
* *Recommended:* RTX 30-series GPU or higher.

**Cloning the Repo:**
```bash
# Ensure LFS is initialized before cloning
git lfs install

# Clone the repository
git clone <repository-url>