<h1 align="center">Hi 👋, I'm Anshuman Tripathy</h1>
<p align="center">
  Electronics & Computer Enthusiast · Hardware Hacker · Embedded Developer
</p>

<p align="center">
  <a href="mailto:anshumantripathy1617@gmail.com"><b>Email</b></a> ·
  <a href="https://github.com/ANSHUMANDOCX?tab=repositories"><b>All Repos</b></a>
</p>

<p align="center">
  <a href="#-projects">Projects</a> ·
  <a href="#-tech">Tech</a> ·
  <a href="#-learning">Learning</a> ·
  <a href="#-stats">Stats</a>
</p>

<hr/>

## 👋 About
I build **hardware-to-firmware projects**: custom PCBs, embedded devices, and small tools that solve real problems.
I enjoy **board bring-up**, **embedded C/C++**, and designing in **KiCad**.

---

## 🔥 Projects

### Quick Index (scan-first)
| Project | What it is | Stack |
|---|---|---|
| **Macropad V2** | 20-key RP2040 macropad with encoders, sliders, OLED, RGB | RP2040 · CircuitPython/KMK |
| **Desk Display** | ESP32 + E‑Ink desk display with Wi‑Fi time + to‑do UI | ESP32 · E‑Ink |
| **USB‑C Audio Hub** | USB‑C hub + TRRS audio in/out (driverless) | USB · PCM2912A |
| **Spot Welder (MCU)** | High-current pulse controller with OLED + encoder UI | ATmega328P |
| **Study Tracker** | ESP32 + OLED productivity tracker + web dashboard + CSV logs | ESP32 · Web UI |
| **MP3 Decoder** | Portable MP3 player PCB (DFPlayer Mini + OLED + charging) | ATmega328P |

> Tip: expand a project below for details.

---

<details>
<summary><b>⌨️ Macropad V2 (RP2040)</b> — custom input device with OLED/encoders/RGB</summary>

**Repo:** https://github.com/ANSHUMANDOCX/Macropad_V2

**Highlights**
- 20 MX-style keys
- 2 rotary encoders
- 2 analog slide potentiometers
- 0.91" SSD1306 OLED (Qwiic)
- WS2812B 2020 RGB underglow
- Firmware direction: KMK / CircuitPython

**Why it’s cool**
- A complete “product-style” build: PCB + enclosure + UI + firmware path.

</details>

<details>
<summary><b>🖥️ Desk Display (ESP32 + E‑Ink)</b> — day/date/time + to‑do</summary>

**Repo:** https://github.com/ANSHUMANDOCX/Desk-Display

**Core idea**
- E‑Ink display for low-power always-on information.
- ESP32 fetches time/date over Wi‑Fi; to‑do list updated from a web page hosted on the ESP32.

**Hardware notes**
- USB‑C powered (not battery-first)
- CH343P USB‑UART + a switch to disable it outside programming

</details>

<details>
<summary><b>🔌 USB‑C Audio + USB Hub</b> — hub + TRRS headset audio</summary>

**Repo:** https://github.com/ANSHUMANDOCX/USB-C-AUDIO-HUB

**What it is**
- USB‑C hub with audio out/in via TRRS jack.

**Highlights**
- 3 downstream USB‑C ports + 1 upstream USB‑C input
- Uses PCM2912A + SL2.1A
- Driverless usage (no firmware flashing)
- BOM + assembly info included

</details>

<details>
<summary><b>⚡ Spot Welder with MCU</b> — pulse timing UI + high current switching</summary>

**Repo:** https://github.com/ANSHUMANDOCX/Spot-Welder-with-MCU

**Highlights**
- IRFB7430 MOSFET-based switching
- ATmega328P + OLED + rotary encoder UI
- Panelized 2-PCB approach to reduce PCB cost
- Mechanical/current-handling considerations (aluminum parts)

**Note**
- Repo mentions firmware is not tested yet on the design.

</details>

<details>
<summary><b>📚 ESP32 OLED Study Tracker</b> — web dashboard + logs + CSV export</summary>

**Repo:** https://github.com/ANSHUMANDOCX/ESP32-OLED-Study-Tracker

**Highlights**
- Track study/work time per subject
- Web page hosted on ESP32 for dashboard + targets
- Log system + download logs as CSV

</details>

<details>
<summary><b>🎵 MP3 Decoder / Portable MP3 Player</b> — offline MP3 player PCB</summary>

**Repo:** https://github.com/ANSHUMANDOCX/MP3-Decoder

**Highlights**
- ATmega328P MCU
- DFPlayer Mini (DFR0299) MP3 module
- 0.96" 128×64 OLED UI
- TP4056 onboard charging
- Physical playback buttons + debug/power LEDs

**Note**
- Repo marks firmware as untested.

</details>

---

## 🛠 Tech
<a name="-tech"></a>

**Hardware / Embedded:** `ESP32` `RP2040` `ATmega328P` `USB` `I2C` `SPI` `UART`  
**Firmware / Software:** `C/C++` `Arduino` `CircuitPython` `MicroPython` `Python`  
**Design / Tools:** `KiCad` `Fusion 360` `VS Code` `Git`

---

## 🧭 Learning
<a name="-learning"></a>

- RTOS concepts for microcontrollers
- Better documentation & project presentation (test notes, bring-up logs, BOMs)

---

## 📈 Stats
<a name="-stats"></a>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ANSHUMANDOCX&show_icons=true&theme=radical" width="49.5%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ANSHUMANDOCX&theme=radical" width="49.5%" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ANSHUMANDOCX&layout=compact&theme=radical" />
</p>

---

## 💬 Contact
- 📧 `anshumantripathy1617@gmail.com`
