<h1 align="center">
  cs2-sdk
  <br>
  <img src="https://img.shields.io/badge/game-CS2-yellow" />
  <img src="https://img.shields.io/badge/language-C%2B%2B-%23f34b7d.svg" />
  <img src="https://img.shields.io/badge/platform-Windows-blue" />
  <img src="https://img.shields.io/badge/platform-Linux-purple" />
  <img src="https://img.shields.io/badge/license-MIT-green" />
</h1>

## 📖 Overview
A lightweight, cross-platform **Counter-Strike 2 SDK** written in C++. Designed for simplicity and performance, this base stays as close as possible to the Source 2 engine structure. It provides a solid foundation for development with native support for both **DirectX 11** and **Vulkan**.

### What's New in v2?
- **Cross-Platform:** Full support for both Windows and Linux.
- **Refactored Core:** Cleaned up base logic for better stability.
- **Maintenance:** Removed high-maintenance features like 'Inventory Changer' to focus on core SDK reliability. 
  - *Note: v1 is still available [here](https://github.com/bruhmoment21/cs2-sdk/tree/v1).*

---

## 🚀 Features
- [x] **Renderer:** Support for DX11 and Vulkan.
- [x] **Input:** SDL3 integration for cross-platform input handling.
- [x] **Hooking:** Advanced trampoline hooking for engine functions.
- [x] **Schema:** Automated Source 2 schema system synchronization.
- [x] **GUI:** Integrated ImGui for debugging and menus.

---

## 🛠 Building
### Requirements
- **Windows:** Visual Studio 2022 (Desktop development with C++).
- **Linux:** `GCC` or `Clang`, `CMake`, and `SDL3` development headers.

#### Windows
1. Open `cs2-sdk.sln`.
2. Set configuration to `Release | x64`.
3. Build Solution (`Ctrl+Shift+B`).

#### Linux
```bash
mkdir build && cd build
cmake ..
make
