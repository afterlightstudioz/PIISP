<div align="center">

# 🎮 PiiSP

### *Unleashing PSP Emulation on Native Nintendo Wii Hardware*

![Status](https://img.shields.io/badge/Status-Early_Development-red?style=for-the-badge&logo=git&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Nintendo_Wii-00ADEE?style=for-the-badge&logo=nintendo-wii&logoColor=white)
![CPU Target](https://img.shields.io/badge/Architecture-PowerPC_Broadway-FF6600?style=for-the-badge&logo=cpu&logoColor=white)
![Source](https://img.shields.io/badge/Core-100%25_From_Scratch-00C853?style=for-the-badge)

<br>

<img width="900" alt="PiiSP Banner Showcase" src="https://github.com/user-attachments/assets/7afc3745-618e-4035-9712-81a96690b102" />

---

### ⚡ **MIPS32 → PowerPC Dynamic Translation**
*Rewriting the rules of what 2006 hardware can achieve.*

[Overview](#-overview) • [Key Features](#-key-features) • [Roadmap & Release](#-roadmap--release) • [Current Status](#-project-status)

---

</div>

## 📌 Overview

**PiiSP** is an experimental, ground-up PlayStation Portable emulator engineered explicitly for the Nintendo Wii. 

Rather than relying on existing codebases or ported cores, PiiSP features a bespoke **MIPS-to-PowerPC JIT recompiler**. It translates the PSP's 333 MHz MIPS32 instructions into native PowerPC instructions on the fly for the Wii's 729 MHz Broadway processor.

> **The Goal:** Prove that a console with only **88 MB of RAM** and a **729 MHz CPU** can emulate a full 7th-gen handheld—without taking shortcuts.

---

## 🛠️ Key Features

<table>
  <tr>
    <td width="50%">
      <h3>⚡ Custom JIT Recompiler</h3>
      <p>Direct MIPS32-to-PowerPC dynamic translation optimized specifically for the Wii's CPU architecture.</p>
    </td>
    <td width="50%">
      <h3>🧩 100% In-House Core</h3>
      <p>Zero borrowed code, zero external forks. Every decoder, memory mapping layer, and register state was built from scratch.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>💾 Memory Efficiency</h3>
      <p>Fine-tuned memory manager designed to maximize performance within the Wii's strict 88 MB RAM constraint.</p>
    </td>
    <td width="50%">
      <h3>🎯 Hardware Native</h3>
      <p>Tailored directly to the hardware limits of the IBM Broadway CPU for maximum cycle-accurate throughput.</p>
    </td>
  </tr>
</table>

---

## 🗓️ Roadmap & Release Target

<div align="center">
</div>

We are currently targeting an initial public release window around **November – December 2026**. Progress is ongoing as core hardware registers, GPU pass-throughs, and audio pipelines are constructed.

---

## 🚨 Project Status

> [!CAUTION]
> **🔴 EARLY IN DEVELOPMENT**  
> PiiSP is currently a heavy work-in-progress proof of concept. Expect low game compatibility, missing audio/video subsystems, and breaking updates as core features are finalized.
