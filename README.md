# Project Name (Replace with your project name)

This project is a customized build of the **TOTEM Keyboard**. It features a modified firmware applied to the **TOTEM Redux** case design.

## 🛠 Project Components & Modifications
- **Hardware (Case):** [TOTEM Redux](https://www.printables.com/model/840146-totem-redux) by **VOID**. (A supportless FDM-friendly remix of the original TOTEM).
- **Hardware (Original Design):** [TOTEM](https://github.com) by **GEIGEIGEIST**.
- **Firmware:** Custom firmware and keymap configurations modified by me to suit my personal setup.

## 📜 License

This project is a derivative work and is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)** license.

To comply with this license, you must adhere to the following:
1. **Attribution:** You must give appropriate credit to the original creators (**GEIGEIGEIST** and **VOID**) and provide links to their respective projects.
2. **Non-Commercial:** You may NOT use this material for commercial purposes (e.g., selling built keyboards, cases, or kits).
3. **ShareAlike:** If you remix, transform, or build upon the material, you must distribute your contributions under the same license (CC BY-NC-SA 4.0).

Full license details can be found [here](https://creativecommons.org).

---
**Credits:**
- Original TOTEM Design by [GEIGEIGEIST](https://github.com)
- TOTEM Redux Case Mod by [VOID](https://printables.com)



Totem Keyboard: Custom Auto-Brightness Edition
A customized build of the Totem Keyboard, featuring silent linear switches, custom resin keycaps, and an integrated ambient light sensor for dynamic display control.

🚀 Overview
This project takes the ergonomic excellence of the Totem keyboard and adds a high-fidelity visual interface. By integrating an ST7789 1.54-inch display and an APDS-9930 ambient light sensor, the keyboard's screen automatically adjusts its brightness based on your environment, ensuring optimal visibility and eye comfort at all times.

✨ Key Features
Silent Linear Switches: Built with silent linear switches for a smooth, quiet typing experience—perfect for office or nighttime use.

Custom KLP-Lame Keycaps: Outfitted with KLP-Lame Keycaps printed in high-quality Gray Resin for a premium tactile feel and sleek aesthetic.

Dynamic Display: A 1.54-inch ST7789 LCD dongle provides crisp visuals.

Auto-Brightness (APDS-9930): Features an integrated proximity and ambient light sensor that adjusts the display backlight in real-time.

Modified "Snake Project" Case: A custom-modified version of the Snake Project case, specifically redesigned to house the sensor assembly and display components seamlessly.

🛠 Hardware Specifications
Component	Detail
PCB	Totem (Split Columnar Stagger)
Switches	Silent Linear Type
Keycaps	Custom Resin (KLP-Lame Design)
Display	1.54" ST7789 (Dongle-mounted)
Sensor	APDS-9930 (Ambient Light & Proximity)
Enclosure	Modified Snake Project Case
<img width="4096" height="3072" alt="IMG_20260505_200542787" src="https://github.com/user-attachments/assets/971f042e-683b-491c-833f-8375a44eec26" />
Totem incl. ZMK Studio

🔧 Technical Implementation
Display & Light Sensing

The heart of this mod is the feedback loop between the APDS-9930 and the ST7789 display. The sensor communicates via I2C to detect lux levels, which the firmware then uses to map the PWM duty cycle of the display's backlight pin (VCC/LEDA).

Case Modification

The case was modified from the original Snake Project files to include:

A dedicated aperture for the APDS-9930 sensor.

Reinforced mounting points for the 1.54-inch display dongle.

Optimized internal cable routing for the additional I2C wiring.

📸 Gallery
(Note: Add your build photos here to show off that gray resin and the glowing display!)

📜 Credits & References
Totem Keyboard: GEIGEIGEIST

Keycap Design: braindefender/KLP-Lame-Keycaps

Dongle Case Inspiration: Snake Project [
(https://github.com/felixJR123/Snake-Dongle-Case)]

"This repo only supports dongleless Totems."
