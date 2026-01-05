---
layout: "default"
title: "📺 ESP32-Desktop-Monitor - Stream Your Screen Effortlessly"
description: "📺 Stream your computer screen to an ESP32 T-Display over WiFi, enabling easy access to your monitor on a compact 1.14" LCD display."
---
# 📺 ESP32-Desktop-Monitor - Stream Your Screen Effortlessly

[![Download Now](https://img.shields.io/badge/Download-Now-brightgreen)](https://github.com/youcef-islam/ESP32-Desktop-Monitor/releases) 

## 🚀 Getting Started

Follow these steps to start streaming your computer screen to an ESP32 T-Display.

### 📦 Download & Install

Visit this page to download: [ESP32-Desktop-Monitor Releases](https://github.com/youcef-islam/ESP32-Desktop-Monitor/releases).

### 🖥️ Hardware Requirements

#### ESP32 Development Board
- **Board**: TENSTAR T-Display ESP32-D0WD (or similar)
- **Chip**: ESP32-D0WD with CH9102 USB-to-Serial chip
- **Memory**: 16MB Flash
- **Display**: 1.14" ST7789 LCD (135x240 pixels)
- **Connectivity**: WiFi and Bluetooth compatible

#### Computer
- Any computer running **Python 3.7+**
- Supported Operating Systems: macOS, Linux, or Windows (with necessary screen capture libraries).

### 💻 Software Requirements

#### ESP32 Side (Arduino IDE)
1. **Install Arduino IDE**
   - Use version 1.8.x or 2.x.
   - Alternatively, you can use **PlatformIO**.

2. **Add ESP32 Board Support Package**
   - Open your Arduino IDE.
   - Navigate to **Preferences**.
   - In the **Additional Board Manager URLs** field, add this link:
     ```
     https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
     ```
   - Go to **Tools > Board > Board Manager**.
   - Search for **"esp32"** and install the version by Espressif Systems.

3. **Install Required Libraries**
   - You may need to install additional libraries to ensure smooth functionality. Check the repository for a list.

### 💡 How to Connect

1. **Connect the ESP32 T-Display** to your computer using a USB cable.
2. **Select the correct COM port** in Arduino IDE. You can find it under **Tools > Port**. Choose the port assigned to your ESP32.
3. **Upload the example code** provided in the repository. Follow the code instructions carefully.
4. **Open your preferred terminal** or command prompt and run the Python application to start the screen mirroring process.

### 🎥 How to Stream Your Screen

1. **Launch the Python Application** on your computer.
2. **Choose the screen or window** you want to share.
3. **Ensure the ESP32 is connected** to the same WiFi network as your computer.
4. **Start the streaming** by following the application’s prompts.

### 🛠️ Troubleshooting

- **ESP32 Not Connecting**: Make sure your ESP32 is connected to the same WiFi as your computer. Check the network settings within the application.
- **Display Issues**: Verify that the correct libraries are installed in Arduino IDE. Ensure display connections are secure.
- **Lag in Streaming**: Close unnecessary applications on your computer. A better network connection will reduce lag.

### 📝 Features

- Stream real-time content from your computer to your ESP32.
- Use a simple user interface for choosing what to display.
- Compatible with commonly used operating systems.
- Lightweight application that runs smoothly in most environments.

### 📜 Notes

- Make sure your ESP32 board has the latest firmware updates.
- Regularly check for updates on the repository to enjoy new features or fixes.

### 🛡️ License

This project is open-source. You can use it freely, but be sure to give credit where it’s due.

### 📍 Additional Resources

For more information, guides, or to report issues, visit our [community forum](https://github.com/youcef-islam/ESP32-Desktop-Monitor/issues).

[![Download Now](https://img.shields.io/badge/Download-Now-brightgreen)](https://github.com/youcef-islam/ESP32-Desktop-Monitor/releases)