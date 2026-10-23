<div align="center">

# PiiSP

**A from-scratch PlayStation Portable (PSP) emulator for the Nintendo Wii.**

![Status](https://img.shields.io/badge/status-early%20development-red.svg)
![Platform](https://img.shields.io/badge/platform-Nintendo%20Wii-blue.svg)
![Target](https://img.shields.io/badge/architecture-PowerPC-orange.svg)

<br>

![piisp-Photoroom](https://github.com/user-attachments/assets/7afc3745-618e-4035-9712-81a96690b102)

</div>

---

## Overview

**PiiSP** is an experimental, independent PlayStation Portable emulator engineered specifically for Nintendo Wii hardware. Written entirely in-house, it features a custom **MIPS-to-PowerPC JIT recompiler** designed to translate the PSP's 333 MHz MIPS32 architecture into native PowerPC instructions for the Wii's 729 MHz Broadway processor on the fly.

Built completely from the ground up with no forks or borrowed emulation cores, every component—from the instruction decoder to the memory manager—was written specifically for this project. The goal is to push the boundaries of the hardware and prove what's possible on a 2006 console with 88 MB of RAM.

## Technical Highlights

* **Custom JIT Recompiler:** Translates MIPS32 instructions directly to native PowerPC machine code at runtime.
* **Independent Architecture:** 100% from-scratch implementation with no external core dependencies or borrowed code.
* **Hardware Constraints:** Optimized specifically for the Wii's IBM Broadway CPU (729 MHz) and constrained memory footprint.

## Project Status

> [!WARNING]
> **🔴 Early in Development**
> PiiSP is currently a work-in-progress proof of concept. Expect frequent updates, missing features, and low compatibility as core subsystems are built and refined.
