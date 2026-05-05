# Totem ZMK: Custom Auto-Brightness Edition

This project is a customized build of the **TOTEM Keyboard**, featuring modified firmware with ZMK Studio support and a customized hardware setup.

## 🛠 Project Components & Modifications

- **Firmware:** Custom ZMK firmware including:
  - **ZMK Studio** support for real-time keymap editing.
  - **Auto-Brightness:** Integrated **APDS-9930** sensor to automatically adjust the display and peripheral brightness based on ambient light.
- **Hardware (Case):** [TOTEM Redux](https://printables.com) by **VOID**.
  - Modified based on the "Snake Project" case to seamlessly integrate the APDS-9930 sensor and display components.
- **Hardware (Original Design):** [TOTEM](https://github.com) by **GEIGEIGEIST**.

## 📜 License

This project is a derivative work and is licensed under the **CERN Open Hardware Licence Version 2 - Permissive (CERN-OHL-P-2.0)**, following the license of the original TOTEM project.

To comply with this license:
1. **Attribution:** You must retain the original copyright notices in the files and provide credit to the original creators (**GEIGEIGEIST** and **VOID**).
2. **Freedom to Modify & Distribute:** You are free to use, modify, and distribute this project (even for commercial purposes, as permitted by CERN-OHL-P-2.0).

Full license details can be found in the [LICENSE](./LICENSE) file or on the [CERN OHL website](https://ohwr.org).

---

**Credits:**
- Original TOTEM Design: [GEIGEIGEIST](https://github.com)
- TOTEM Redux Case: [VOID](https://printables.com)
- Firmware Customization: [5h100ky](https://github.com)




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
