#PulseV1

**PulseV1** is a compact, 18650-powered, CircuitPython-based multifunction gadget. Designed for portability and versatility, it features music playback, lighting modes, meditation guidance, timers, and an interactive OLED interface — all controlled by a single button. Ideal for learning, tinkering, or just carrying a little tech fun in your pocket.

---

## ⚡ Key Features

- 🧠 **Single-Button Menu Interface**  
  Navigate a list of features using short and long presses.

- 🖥️ **OLED Display (128x32)**  
  Shows menu items, timers, and animation text.

- 🌈 **NeoPixel RGB LED**  
  Used for mood lighting, strobe, and breathing effects.

- 🔊 **Piezo Buzzer (D10)**  
  Plays sound effects and melodies like the Star Trek theme.

- 🔋 **Powered by 18650 Li-ion Battery**  
  Rechargeable and portable, built into the design.

- 🔌 **TP4056 Charging Module with Dual MOSFET Protection**  
  Enables safe USB charging and output at the same time without risk of back-charging the USB source.

---

## 🧰 Hardware List

| Component                | Description                                     |
|--------------------------|-------------------------------------------------|
| MCU Board                | Seeed Studio XIAO or RP2040-compatible          |
| OLED Display             | SSD1306 128x32 I2C                              |
| Buzzer                   | Piezo (connected to D10)                        |
| Button                   | Digital input (connected to D9)                |
| Battery                  | 18650 Lithium-Ion cell                          |
| Charging Module          | TP4056 w/ protection                            |
| Optional Power Switch    | For toggling the whole unit                    |

---

## 🧠 Modes & Functions

- **🎵 Star Trek Theme** – Plays a melody using the piezo buzzer.
- **🌈 Rainbow LED** – Cycles through a full RGB spectrum.
- **⏱️ Timer** – Choose from 10s, 30s, or 60s countdowns with visual/audible feedback.
- **🧘 Meditation** – Breathing guide with visuals and tones.
- **🎞️ Animation** – Frame-based light/text animation.
- **🔦 Flashlight** – Full-bright white LED mode.
- **⚡ Strobe** – Rapid blinking white LED.
- **😴 Sleep Mode** – OLED off, lights off, waits for button press to reawaken.

---

## 🧪 Usage Instructions

1. **Power On** – Toggle switch if present.
2. **Cycle Menu** – Tap the button to scroll through available modes.
3. **Select Mode** – Hold the button for ~1 second to activate.
4. **Exit Mode** – Hold button in most modes for ~1.5–2 seconds to return.


---

## 🔌 Power & Charging

- The TP4056 module with protection IC safely charges the 18650 cell via micro-USB.
- Two external MOSFETs are added to **prevent back-charging the USB source** while allowing the device to run off the battery.
- System is designed to run continuously while charging, making it ideal for stationary or portable use.

---
