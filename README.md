# 🔥OCSKI🔥

<p align="center">
  <img src="https://img.shields.io/badge/.NET-6.0-512BD4?style=flat-square" alt=".NET 6.0">
  <img src="https://img.shields.io/badge/Platform-Windows-0078D6?style=flat-square" alt="Windows">
  <img src="https://img.shields.io/badge/GPU-NVIDIA-76B900?style=flat-square" alt="NVIDIA">
</p>

A sleek Windows GPU overclocking utility for NVIDIA graphics cards with real-time monitoring, profile management, and Qubic mining phase synchronization.

## Features

- **Real-time GPU Monitoring** - Core clock, memory clock, temperature, usage, and power draw
- **Clock Offsets** - Adjust core and memory clock offsets with slider controls
- **Clock Locking** - Lock GPU and memory clocks to specific frequencies
- **Power Limit Control** - Set custom power limits in watts
- **Profile System** - Save and load up to 3 OC profiles (left-click to load, right-click to save)
- **Qubic Sync** - Automatically switch OC settings based on Qubic mining phases (Training/Idle)
- **Startup Options** - Start with Windows and start minimized

<img width="915" height="587" alt="image" src="https://github.com/user-attachments/assets/3aa2097d-8f43-4cdf-a55b-0fdd4cbc795c" />


## Requirements

- Windows 10/11
- NVIDIA GPU with recent drivers
- .NET 6.0 Runtime
- Administrator privileges (required for GPU control)

## Installation

1. Download the latest release from [Releases](../../releases)
2. Extract to a folder of your choice
3. Run `OCSKI.exe` as Administrator

## Usage

### Basic Overclocking

1. Adjust **Core** and **Memory** sliders to set clock offsets
2. Click **APPLY** to apply each offset
3. Set **Power Limit** in watts and click **APPLY**
4. Use **Lock Core/Memory** to lock clocks to specific frequencies

### Profiles

- **Right-click** on P1, P2, or P3 to save current settings
- **Left-click** to load a saved profile
- **Left-click** on active (red) profile to unload and reset to defaults
- Profiles save: offsets, power limit, locked clocks, and Qubic Sync settings

### Qubic Sync

Automatically switches between two OC configurations based on Qubic mining phases:

1. Enable **QUBIC SYNC** checkbox
2. Configure **⚡ TRAINING** row - OCs applied during AI training phase
3. Configure **💤 IDLE** row - OCs applied during idle phase
4. Click **SAVE** to save and apply settings

### Settings

Click the **⚙** gear icon to access:
- **Start with Windows** - Launch OCSKI on system startup
- **Start minimized** - Start in minimized state

<img width="912" height="266" alt="image" src="https://github.com/user-attachments/assets/9bb13514-c09e-4ed8-a2c1-d01b7766fefe" />


## Disclaimer

Overclocking your GPU can cause system instability, crashes, or hardware damage. Use at your own risk. The authors are not responsible for any damage caused by using this software.
