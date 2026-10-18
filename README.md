```text
     _ _cm_             _   __  __ __  __ _   _ 
  __| (_)_ __ ___  ___ | |_|  \/  |  \/  | | | |
 / _` | | '__/ _ \/ __|| __| |\/| | |\/| | | | |
| (_| | | | |  __/ (__ | |_| |  | | |  | | |_| |
 \__,_|_|_|  \___|\___| \__|_|  |_|_|  |_|\___/ 
             directMMU for Voron 2.4
```

# 🦝 directMMU for Voron 2.4

**directMMU** is a compact, robust, and reliable multi-material system featuring a direct filament path, designed specifically for **Voron 2.4** 3D printers.

The core philosophy of **directMMU** is to minimize filament resistance, eliminate overly complex mechanisms, and provide smooth, trouble-free color changes without jams.

---

## ✨ Features
- 🎯 **Direct Filament Path:** Short and straight travel path reduces friction, preventing jams and improving reliability.
- 🛠 **Easy Assembly:** Designed with a minimal part count and standard, easy-to-source hardware.
- ⚙️ **Klipper Native:** Easy integration with Klipper and full compatibility with [Happy Hare v4 (ERCF v2)](https://github.com/moggieuk/Happy-Hare).
- 📐 **Scalable:** Fits all standard Voron 2.4 build sizes (250 / 300 / 350 mm).

---

## 🖨 Print Settings

Follow standard **Voron Design** printing guidelines:
- **Material:** ABS or ASA
- **Layer Height:** 0.2 mm
- **Infill:** 40% (Grid or Gyroid)
- **Perimeters:** 4
- **Top/Bottom Layers:** 5 / 5

> 💡 *All STL files are pre-oriented in their recommended printing positions (no supports required).*

---

## 🔩 Bill of Materials (BOM)

### Electronics
- Stepper Motors — *1 pc per dock*
- Filament Sensors / Switches — *2 pcs per dock*
- Control Board (e.g., BTT B36V / CANbus board) — *1 pc*

### Hardware & Fasteners
- Bearings (608 2RS / F695 2RS) — *X pcs*
- Brass Heat-Set Inserts (M3x5x4) — *X pcs*
- M3 Screws (various lengths) — *See `/Docs` for details*

---

## 📂 Repository Structure

```text
directMMU/
├── CAD/                     # STEP, F3D source files
├── STLs/                    # Ready-to-print 3D models
│   ├── [a]_accent_parts/    # Accent color parts
│   └── primary_parts/       # Primary color parts
├── Klipper/                 # Configuration files (.cfg)
├── Docs/                    # Assembly guides and detailed BOM
└── LICENSE                  # CC BY-NC 4.0 License
```

---

## 📜 License & Commercial Usage

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license.

- **Non-Commercial Use:** You are free to download, print, and modify this project for personal use.
- **Commercial Use:** Selling printed parts, commercial kits, or using this design for commercial services **is strictly prohibited without prior permission from the author**.

📫 For commercial licensing inquiries or permission:
- **Email:** `banstalker@gmail.com`
- **Telegram:** `@banstalker`