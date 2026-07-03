# 🔊 Analog Audio Amplifier with Tone Control, ESP32 MP3 Decoding & Ultrasonic Volume Control

<p align="center">

![ESP32](https://img.shields.io/badge/ESP32-Microcontroller-E7352C?style=for-the-badge&logo=espressif)
![MATLAB](https://img.shields.io/badge/MATLAB-Signal%20Analysis-orange?style=for-the-badge&logo=mathworks)
![Multisim](https://img.shields.io/badge/NI-Multisim-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</p>

---

# 📖 Overview

The **Analog Audio Amplifier with Tone Control, ESP32 MP3 Decoding & Ultrasonic Volume Control** is an embedded electronics project that combines modern digital audio processing with a high-quality analog amplification system.

The system uses an **ESP32 microcontroller** to decode MP3 files from an SD card and stream audio to a **NE5532-based active tone control circuit**. The processed signal is amplified using a **Class-AB Power Amplifier** built with discrete transistors. Two **HC-SR04 Ultrasonic Sensors** provide touchless gesture-based volume and mute control, creating an intuitive Human-Computer Interaction (HCI) experience.

---

# ✨ Features

- 🎵 ESP32 MP3 Audio Playback
- 🎚️ Active Bass & Treble Tone Control
- 🔊 Class-AB Audio Amplifier
- 📀 SD Card Audio Support
- 🤚 Ultrasonic Gesture-Based Volume Control
- 🔇 Touchless Mute Control
- 📈 MATLAB Signal Analysis
- ⚡ Multisim Circuit Simulation
- 🎛️ Low Distortion Audio Output
- 🖥️ Embedded Audio Processing

---

# 🔧 Hardware Requirements

- ESP32 Development Board
- NE5532 Tone Control Module
- BD139 Transistor
- BD140 Transistor
- BC109BP Transistor
- 2N3906 Transistor
- HC-SR04 Ultrasonic Sensors
- Relay Module
- Speaker (8Ω)
- MicroSD Card Module
- Capacitors & Resistors
- Breadboard / PCB
- Jumper Wires
- Power Supply

---

# 💻 Software Requirements

- Arduino IDE
- MATLAB
- NI Multisim
- ESP32 AudioI2S Library

---

# 📂 Project Structure

```text
Analog-Audio-Amplifier-ESP32
│
├── ESP32 Code/
│      amplifier.ino
│
├── MATLAB/
│      signal_analysis.m
│
├── Circuit Diagrams/
│      amplifier_circuit.png
│      tone_control.png
│
├── Simulation/
│      multisim_output.png
│
├── Images/
│      hardware_setup.jpg
│      waveform.png
│
├── Report/
│      Project_Report.pdf
│
├── README.md
├── LICENSE
└── .gitignore
```

---

# ⚙️ Working Principle

1. MP3 files are stored on the SD Card.
2. ESP32 decodes the MP3 audio stream.
3. Audio is transmitted through the I2S interface.
4. NE5532 performs Bass and Treble adjustment.
5. The Class-AB amplifier amplifies the processed audio.
6. HC-SR04 ultrasonic sensors detect hand gestures.
7. Gestures control volume level and mute functionality.
8. Amplified audio is delivered to the speaker.

---

# 📸 Project Images

### Hardware Implementation

<p align="center">
<img src="Images/hardware_setup.jpg" width="700">
</p>

### Tone Control Circuit

<p align="center">
<img src="Circuit Diagrams/tone_control.png" width="700">
</p>

### Class-AB Amplifier Circuit

<p align="center">
<img src="Circuit Diagrams/amplifier_circuit.png" width="700">
</p>

### Output Waveform

<p align="center">
<img src="Simulation/multisim_output.png" width="700">
</p>

---

# 🚀 Applications

- Smart Audio Systems
- Home Audio Amplifiers
- Embedded Audio Devices
- Consumer Electronics
- Gesture-Controlled Electronics
- Educational Embedded Systems
- Analog & Digital Audio Processing

---

# 🔮 Future Scope

- Bluetooth Audio Streaming
- OLED Display Integration
- Mobile App Control
- Wi-Fi Audio Streaming
- DSP-Based Audio Equalizer
- Voice Assistant Integration
- AI-Based Gesture Recognition
- Class-D Amplifier Upgrade

---

# 👨‍💻 Authors

- **Srajan Gupta**
- Saksham Arora
- Daspati Anuraag Prahas
- Surya Pratap Singh

**B.Tech Electronics and Communication Engineering (ECE)**

**VIT Vellore**

GitHub: https://github.com/xsrajangupta

---

## ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub!

It motivates me to build and share more open-source projects.
