# 🔥OCSKI🔥

<p align="center">
  <img src="https://img.shields.io/badge/version-2.0-FF1744?style=flat-square" alt="Version 2.0">
  <img src="https://img.shields.io/badge/.NET-10-512BD4?style=flat-square" alt=".NET 10">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-0078D6?style=flat-square" alt="Windows 10 and 11">
  <img src="https://img.shields.io/badge/GPU-NVIDIA-76B900?style=flat-square" alt="NVIDIA">
</p>

A sleek Windows overclocking utility for NVIDIA graphics cards: live monitoring, clock offsets, clock locks and caps, power limits, and per-GPU profiles, with a safety net that restores your settings when something goes wrong.

<img width="600" alt="main" src="https://github.com/user-attachments/assets/d268e613-c762-4aef-b5e3-9712e77e4f6a" />


## Features

- **Live monitoring**: core and memory clocks, temperature, load, power draw, VRAM use, and fan speed (when the driver reports one), plus driver and VBIOS versions.
- **90-second graph** of temperature, power, core clock, and memory clock. Click a legend entry to show or hide its line.
- **Active line** that shows what differs from stock right now: profile, offsets, locks or caps, and power limit.
- **Limit indicator** that shows why the driver is holding the clocks back: power limit, temperature target, clock setting, idle, or hardware slowdown. Hardware protection (overheating, power brake) shows in red.
- **Clock offsets**: drag the slider, or type an exact value and press Enter. Up/Down change it by 1 MHz, Shift+Up/Down by 10 MHz.
- **Clock locks and caps**: **FIXED** holds one clock. **CAP** limits the maximum clock but still lets the GPU slow down at idle; a cap combined with a positive core offset is an easy undervolt.
- **Power limit** control on GPUs whose driver allows it.
- **Three profiles per GPU**, stored by GPU identity so multi-GPU systems keep separate profiles. Export and import them as files.
- **Safe changes**: every apply must be confirmed with **Keep for session** within 20 seconds, or it reverts automatically.
- **Crash recovery**: OCSKI records each change before making it. If it crashes or is killed, the next launch restores your GPU, and it skips the launch profile once so a bad overclock cannot crash your system again at sign-in.
- **Restores on exit**, including when Windows signs out or shuts down.
- **Notification-area icon** with a quick menu to apply profiles, reset to defaults, or exit.
- **Launch profile**: optionally apply a profile when OCSKI starts.
- **Custom dark window** with 100%, 115%, and 130% UI sizes.
- **Light on laptops**: OCSKI stops polling the GPU while minimized so a laptop's NVIDIA GPU can power down.

## Disclaimer

Overclocking your GPU can cause system instability, crashes, or hardware damage. Use at your own risk.

---

<p align="center"><sub>LICENSED UNDER ANTI-MILITARY LICENSE</sub></p>
