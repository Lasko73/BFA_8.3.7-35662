# World of Warcraft – Battle for Azeroth 8.3.7 (Build 35662) TrinityCore

A fully open-source project dedicated to preserving and improving the Battle for Azeroth 8.3.7 experience using TrinityCore.  
Focused on **stability**, **retail-like accuracy**, and **community-driven updates**.

---

## Features
- Full compatibility with WoW client **8.3.7 (Build 35662)**.
- Retail-like quest and NPC behavior.
- Active community collaboration for continuous fixes and enhancements.
- Structured development for custom or retail-like private servers.

---

## Goals
- Provide a clean and stable 8.3.7 core for private server developers.
- Encourage contributions to improve scripts, quests, battlegrounds, and world data.
- Maintain long-term support for BFA content.

---

## How to Contribute
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/AmazingFix`).
3. Commit your changes (`git commit -m 'Add AmazingFix'`).
4. Push to the branch (`git push origin feature/AmazingFix`).
5. Open a Pull Request.

---

## Quick Setup

### Requirements
- MySQL/MariaDB
- CMake 3.16+
- Visual Studio 2019/2022 (x64)
- Boost 1.72
- OpenSSL 1.1.x

### Basic Steps
```bash
git clone https://github.com/TU_USUARIO/NOMBRE_DEL_REPO.git
cd NOMBRE_DEL_REPO
mkdir build && cd build
cmake ../ -DTOOLS=1
cmake --build . --config Release
