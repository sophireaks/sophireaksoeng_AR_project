# AR Face Filter — Final Assignment

An augmented reality face-filter app built in **Unity 6 (6000.3.9f1)** with **AR Foundation** and **ARCore**, targeting Android. The app tracks the user's face in real time and overlays 3D props and particle effects, similar to popular social-media face filters.

## Features

- Real-time **face tracking** using AR Foundation's `ARFace` system
- Swappable **3D props** attached to face anchors:
  - Cat Ears, Cat Nose, Goblin Ears, Horns
  - Cap, Hi-Hat, Moustache, Grinning Teeth, Crazy Eyes
- **Particle / VFX effects:**
  - Fire, Rain, Steam, Dizzy stars, Magic Eyes
- Custom reskin and design built on top of the Unity *Create with AR: Face Filters* course base.

## 🛠️ Built With

- Unity 6 LTS (6000.3.9f1)
- AR Foundation + ARCore (Google)
- Universal Render Pipeline (URP)
- New Input System

## Project Structure

```
Assets/
├── _BasicFaceFilter/
│   ├── Prefabs/            # Face props (ears, horns, moustache, etc.)
│   ├── Particle Effects/   # Fire, Rain, Steam, Dizzy, MagicEyes VFX
│   └── ...
├── Scenes/SampleScene.unity
├── Settings/               # URP & quality settings
└── XR/                     # AR / XR configuration
```

> Note: The `Library/`, `Temp/`, and build-output folders are intentionally excluded via `.gitignore` — they are regenerated automatically when the project is opened in Unity.

## How to Run

1. Open the project in **Unity 6 (6000.3.9f1)** or later.
2. Switch platform to **Android** (`File → Build Settings → Android`).
3. Connect an ARCore-supported Android device with USB debugging enabled.
4. Click **Build And Run**.

## Requirements

- Android device with **ARCore support**
- Minimum Android **API level 24 (Android 7.0)**

## Course Reference

Based on Unity Learn — [Create with AR: Face Filters](https://learn.unity.com/course/create-with-ar-face-filters)

---

**Author:** Sophireak Soeng
