# Eco Racing – STM32 Line Follower Car

## 📌 Overview
This project was developed for the **Eco Racing Competition** at Cairo University, Faculty of Engineering, where our team achieved **2nd place overall**.  
It features an **STM32-based autonomous line follower vehicle** with an advanced path correction algorithm designed for high accuracy and reliability.  

Unlike basic line followers that only track a single path, our system uses **dual-line detection** and an intelligent control strategy that can **detect deviation, reverse, and realign** itself, ensuring continuous path following even in challenging track conditions.

---

## 🏆 Achievement
- **2nd Place** – Cairo University & Faculty of Engineering Eco Racing Event.
- Recognized for **robust control logic** and **efficient execution**.
- Certificate awarded (currently misplaced).

---

## ⚙ Hardware Specifications
| Component                | Description                                         |
|--------------------------|-----------------------------------------------------|
| **Microcontroller**      | STM32F103C8T6 (Blue Pill)                            |
| **Sensors**              | 6 × IR line sensors                                  |
| **Motor Driver**         | *[Add model here]*                                   |
| **Motors**               | Common DC geared motors (suitable for robotics use) |
| **Power Source**         | 4 × 4V batteries (16V total)                         |
| **Development Platform** | STM32CubeIDE                                          |

---

## 💡 Features
- **Advanced Line Following** – Tracks between two lines, not just one.
- **Self-Correction** – Can reverse and realign if it drifts off track.
- **6-Sensor Input** – Provides fine-grained path detection and decision-making.
- **STM32 Performance** – Efficient C code running on ARM Cortex-M3 architecture.
- **Energy-Efficient Design** – Optimized control logic for competition efficiency.

---

## 🖥 Software & Development
- **IDE**: STM32CubeIDE
- **Language**: C
- **Firmware**: HAL-based GPIO, ADC, and motor control.
- **Algorithm Highlights**:
  - Reads sensor array continuously.
  - Determines vehicle position relative to track boundaries.
  - Executes PID-like correction logic with additional *reverse-and-retry* strategy.
  - Ensures smooth navigation around curves and during path recovery.

---

## 📷 Media
*(Add photos of your car, competition shots, and diagrams here)*  
- `docs/images/car_front.jpg`
- `docs/images/car_side.jpg`
- `docs/images/competition.jpg`

---

## 🚀 Setup & Usage
1. Connect all hardware as per wiring diagram. *(diagram to be added)*
2. Flash the firmware to the STM32F103C8T6 using STM32CubeProgrammer or ST-Link.
3. Power on with the 16V battery pack.
4. Place the vehicle on the track and watch it navigate autonomously.

---

## 📂 Repository Structure
Eco-Racing/
├── src/ # Main C source code
├── inc/ # Header files
├── docs/ # Documentation & images
├── README.md # Project description
└── LICENSE # License file

---

## 📜 License
This project is released under the [MIT License](LICENSE).  
Feel free to use, modify, and share with attribution.

---

## ✍ Acknowledgements
Special thanks to **Cairo University** and **Faculty of Engineering** for organizing the Eco Racing event and to my teammates for their dedication and collaboration.

