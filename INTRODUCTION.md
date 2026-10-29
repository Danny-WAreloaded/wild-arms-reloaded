# Wild Arms: Reloaded 🌵✨

**Wild Arms: Reloaded** is an enhanced, native PC port and artistic restoration of the original 1996 PlayStation 1 classic. 

This project is a fork of the groundbreaking static recompilation work found in `wild-arms-recomp`. Instead of relying on traditional emulation, the game's original MIPS machine instructions are statically compiled into native x86 C code, creating a lightweight, high-performance executable (`Wild_Arms.exe`) that runs natively on modern operating systems.

---

## 👁️ The Vision

The goal of **Wild Arms: Reloaded** is not a complete graphical remake, but a definitive, premium preservation of the original game's soul. We are leveraging frontier AI tooling, automated upscaling pipelines, and community collaboration to implement features that make the game look and feel right at home on modern displays:

* **True Widescreen (16:9+) Support:** Modifying the original projection matrices to expand the horizontal field of view during 3D battles and 2D overworld exploration, while preserving the original aspect ratio of HUD and menu elements to prevent stretching.
* **Anime-Faithful HD Texture Pack:** Eliminating harsh pixel blockiness by implementing an external texture injection pipeline. We utilize specialized AI upscaling models (like ESRGAN/Waifu2x) trained specifically on anime and cel art art styles to ensure characters, portraits, and environments look crisp and smooth without losing their 1996 aesthetic identity.
* **Modern Quality-of-Life Architecture:** Building the groundwork for asset-dumping loops, custom display shaders, and enhanced control mappings.

---

## 🛠️ Project Status & Direction

This repository acts as the active directorial hub for the *Reloaded* edition. 

* **Phase 1 (Complete):** Core static recompilation framework successfully inherited from upstream.
* **Phase 2 (In Progress):** Integrating the texture-dumping/hashing hooks and auditing the rendering pipeline for widescreen geometry modifications.

*Note: This repository contains no copyrighted game assets, proprietary disc data, or BIOS images. To build and play Wild Arms: Reloaded, users must provide their own legally acquired North American retail disc image (SCUS-94608) and a PS1 BIOS (SCPH-1001).*
