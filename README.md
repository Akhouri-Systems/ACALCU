<p align="center">
  <img src="https://img.shields.io/badge/Status-Archived-lightgrey?style=for-the-badge" alt="Archived">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/GUI-PyQt6-green?style=for-the-badge" alt="PyQt6">
  <img src="https://img.shields.io/badge/License-Proprietary-yellow?style=for-the-badge" alt="License">
</p>

<h1 align="center">ACALCU V3</h1>
<p align="center"><i>World's Most Customizable Scientific Calculator</i></p>

<p align="center">
  <a href="https://github.com/Akhouri-Anmol-Kumar/ACALCU-v3/releases/download/ACALCU/ACALCU.by.Akhouri.Systems.zip">
    <img src="https://img.shields.io/badge/Download-ACALCU%20V3-success?style=for-the-badge&logo=github" alt="Download ACALCU V3">
  </a>
</p>

---

> **📁 Archive Notice:** This project has been officially archived. ACALCU V3 represents the final, feature-complete iteration of this software. It is preserved here as a showcase of advanced PyQt6 UI design, multimedia integration, and deep desktop customization.

## 📖 Overview

ACALCU V3 is far more than a standard calculator. It is a desktop experience that combines rigorous scientific calculations with unprecedented UI customization. From embedding videos inside calculator buttons to growing virtual plants with every calculation, ACALCU pushes the boundaries of what a desktop utility can be.

## ✨ Key Features

### 🧮 Advanced Scientific Engine
* **Comprehensive Math:** Trigonometry (sin, cos, tan), logarithms (log, ln), roots, powers, and constants (π, e).
* **Smart Evaluation:** Safe expression parsing with support for complex chained operations.
* **History Tracking:** Dedicated history dialog to review past calculations and expressions.
* **Full Keyboard Support:** Native mapping for Numpad, operators, Enter, Backspace, and Escape.

### 🎨 30+ Premium Themes
Dynamically switch between meticulously crafted color palettes without restarting the app:
* **Modern & OS:** Windows 7, Windows Vista, Windows 10, OneUI 8.0, Minimal White.
* **Developer & Dark:** Dracula, Nord, Solarized, Monokai, Terminal, Midnight, Cyberpunk.
* **Aesthetic & Fun:** Liquid Glass, Rose Gold, Sakura, Candy, Galaxy, Sunset, Ocean, Fire, Ice, Matrix, Vintage, Forest.
* **Akhouri Originals:** Default Dark, Royal, Gold Dark, and the interactive **Wild** theme.

### 🖼️ Deep Button Customization
* **Right-Click to Edit:** Right-click *any* button on the grid to open the customizer.
* **Visual Overhaul:** Change labels, fonts, font sizes, background colors, and text colors.
* **Multimedia Buttons:** Assign local **Images**, **GIFs**, or even **Videos** (MP4, AVI, etc.) to play directly inside the button boundaries using `QMovie` and `QMediaPlayer`.

### 🌿 Special Interactive Modes
* **The "Wild" Theme:** Features a custom-built `PlantWidget`. Every time you perform a calculation, the plant receives water drops and gradually grows its stem and leaves.
* **"Liquid Glass" Mode:** Enables true window transparency (`WA_TranslucentBackground`) and frameless borders, allowing the calculator to blend seamlessly into your desktop wallpaper.

### 💾 Persistent Configuration
* All custom layouts, theme choices, and button modifications are automatically saved to `acalcu_v3_config.json`.
* Your personalized calculator is exactly as you left it on the next launch.

---

## ⌨️ Keyboard Shortcuts

| Key | Action | Key | Action |
| :--- | :--- | :--- | :--- |
| `0-9` | Input Numbers | `+` `-` `*` `/` | Arithmetic Operators |
| `.` | Decimal Point | `%` | Percentage |
| `Enter` | Equals (`=`) | `Backspace` | Clear Last (`C`) |
| `Esc` | Clear All (`AC`) | | |

---

## 🛠️ Technology Stack

* **Core:** Python 3
* **GUI Framework:** PyQt6 (Qt6)
* **Multimedia:** PyQt6 Multimedia (`QMediaPlayer`, `QVideoWidget`, `QMovie`)
* **Data Persistence:** JSON
* **Math Engine:** Python `math` library with custom safe evaluation context

---

## 🚀 Installation & Usage

1. **Download:** Grab the latest compiled release using the badge at the top of this README.
2. **Extract:** Unzip `ACALCU.by.Akhouri.Systems.zip` to your preferred directory.
3. **Run:** Launch the executable. 
4. **Customize:** Right-click any button to start personalizing your interface, or click the 🎨 icon to browse the 30+ themes.

*Note: If running from source, ensure you have PyQt6 installed via `pip install PyQt6`.*

---

## 🗺️ Project Goals & Legacy

ACALCU V3 was built to prove that utility software doesn't have to be boring. The project focused on:
* **User Agency:** Giving the user total control over the UI grid.
* **Multimedia Integration:** Bridging the gap between standard widgets and video playback.
* **Creative Expression:** Introducing gamified elements (like the Wild theme plant) into productivity tools.

While active development has concluded, the codebase remains a robust reference for PyQt6 developers looking to implement custom painting, media-rich widgets, and dynamic stylesheet generation.

---

## 👨‍💻 Developer

**Akhouri Anmol Kumar**  
*Founder & CEO @ Akhouri Systems*  
*Indian Software Developer*

---

<p align="center">
  <b>ACALCU V3 — Where calculation meets customization.</b><br>
  <i>© 2026 Akhouri Systems. All rights reserved.</i>
</p>
