# ![Banner](https://imgbox.com/zKIwiQ53)
# World of Warcraft – Battle for Azeroth 8.3.7 (Build 35662) TrinityCore

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-TrinityCore-blue)
![WoW Version](https://img.shields.io/badge/WoW-8.3.7%20(35662)-orange)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-yellow)

---

## Introduction / Introducción

**English:**  
A fully open-source project dedicated to preserving and improving the Battle for Azeroth 8.3.7 experience using TrinityCore. Focused on stability, retail-like accuracy, and community-driven updates.  

**Español:**  
Proyecto completamente de código abierto dedicado a preservar y mejorar la experiencia de Battle for Azeroth 8.3.7 usando TrinityCore. Enfocado en estabilidad, precisión tipo retail y actualizaciones impulsadas por la comunidad.  

---

## Features / Características

**English:**  
- Full compatibility with WoW client 8.3.7 (Build 35662)  
- Retail-like quest and NPC behavior  
- Active community collaboration for continuous fixes and enhancements  
- Structured development for custom or retail-like private servers  

**Español:**  
- Compatibilidad total con el cliente WoW 8.3.7 (Build 35662)  
- Comportamiento de misiones y NPCs similar al retail  
- Colaboración activa de la comunidad para correcciones y mejoras continuas  
- Desarrollo estructurado para servidores privados personalizados o tipo retail  

---

## Goals / Objetivos

**English:**  
- Provide a clean and stable 8.3.7 core for private server developers  
- Encourage contributions to improve scripts, quests, battlegrounds, and world data  
- Maintain long-term support for BFA content  

**Español:**  
- Proveer un core limpio y estable para desarrolladores de servidores privados 8.3.7  
- Fomentar contribuciones para mejorar scripts, misiones, campos de batalla y datos del mundo  
- Mantener soporte a largo plazo para el contenido BFA  

---

## How to Contribute / Cómo Contribuir

**English:**  
1. Fork the repository.  
2. Create a feature branch (`git checkout -b feature/AmazingFix`).  
3. Commit your changes (`git commit -m 'Add AmazingFix'`).  
4. Push to the branch (`git push origin feature/AmazingFix`).  
5. Open a Pull Request.  

**Español:**  
1. Haz un fork del repositorio.  
2. Crea una rama para la característica (`git checkout -b feature/AmazingFix`).  
3. Haz commit de tus cambios (`git commit -m 'Add AmazingFix'`).  
4. Haz push a la rama (`git push origin feature/AmazingFix`).  
5. Abre un Pull Request.  

---

## Community / Comunidad

**English:**
Join us to create the most accurate and stable BFA 8.3.7 core available.

**Español:**
Únete para crear el core de BFA 8.3.7 más preciso y estable disponible.

---

## License / Licencia:

**English:**
-This project follows the TrinityCore License.

**Español:**
-Este proyecto sigue la licencia de TrinityCore.

---

## Maintained by LASKO73

---

## Quick Setup / Configuración Rápida
 
### Requirements
- MySQL/MariaDB  
- CMake 3.16+  
- Visual Studio 2019/2022 (x64)  
- Boost 1.72  
- OpenSSL 1.1.x  

### Basic Steps
```bash
git clone https://github.com/Lasko73/BFA_8.3.7-35662.git
cd BFA_8.3.7-35662
mkdir build && cd build
cmake ../ -DTOOLS=1
cmake --build . --config Release




