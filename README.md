# ⚡ StackmatLink - Connect Stackmat Timers to csTimer

[![Download StackmatLink](https://img.shields.io/badge/Download-StackmatLink-brightgreen?style=for-the-badge)](https://github.com/aadilshazeb/StackmatLink)

StackmatLink bridges your standard Stackmat timer to csTimer using an ESP32-S3 device. It uses the GAN Bluetooth Protocol to send the timing data directly to csTimer on your PC. This lets you time your speedcubing solves without cables or extra setup.

---

## 📋 What is StackmatLink?

StackmatLink is a tool designed to connect a Stackmat timer with csTimer software via Bluetooth. It uses an ESP32-S3 chip and speaks the GAN Bluetooth Protocol. This makes timing your solves easier and cleaner by eliminating wiring. You get the timing data transferred wirelessly and ready to use in csTimer.

The software focuses on speedcubing and supports popular timer models. It will help you improve your practice by making the timing process smooth and reliable.

---

## 💻 System Requirements

Before you start, make sure your computer meets these requirements:

- **Operating System:** Windows 10 or later
- **Bluetooth:** Your PC must support Bluetooth Low Energy (BLE)
- **csTimer:** Installed and running on your PC (download from cstimer.net if needed)
- **Hardware:** ESP32-S3 device programmed with StackmatLink firmware
- **Stackmat Timer:** Standard Stackmat timer compatible with GAN Bluetooth Protocol

---

## 🌐 How to Download StackmatLink

Click the button below to visit the GitHub repository for StackmatLink.

[![Download StackmatLink](https://img.shields.io/badge/Download-StackmatLink-blue?style=for-the-badge)](https://github.com/aadilshazeb/StackmatLink)

On the GitHub page, navigate to the **Releases** section to find the latest version. You will see files for the firmware and setup instructions.

---

## 🚀 Getting Started: Step-by-Step Guide

These steps will help you get StackmatLink up and running on your Windows PC. No programming or advanced knowledge is needed.

### 1. Prepare Your ESP32-S3 Device

- Purchase an ESP32-S3 board if you don’t have one. This is a small microcontroller with Bluetooth support.
- You will need to flash the StackmatLink firmware on it. Download the firmware file from the GitHub repository’s Releases page.
- Follow these instructions to flash the firmware:
  - Download and install the **Espressif Flash Download Tool** (search online for the latest Windows version).
  - Connect the ESP32-S3 to your PC via USB.
  - Open the Flash Tool.
  - Select the firmware file you downloaded.
  - Click **Start** to flash the device.
- Once flashing finishes, disconnect the ESP32-S3 from USB and power it with a battery or power bank for portable use.

### 2. Connect Your Stackmat Timer

- Connect your Stackmat timer to the ESP32-S3 device using the correct input ports or cables, depending on your hardware setup.
- Ensure the timer and ESP32-S3 are powered and within Bluetooth range of your PC.

### 3. Set Up Bluetooth on Your Windows PC

- Open **Settings** > **Devices** > **Bluetooth & other devices**.
- Turn on Bluetooth.
- Click **Add Bluetooth or other device** and select Bluetooth.
- Look for a device named similar to “StackmatLink” or with the ESP32-S3 identifier.
- If asked for a PIN or pairing code, use `0000`.
- Once paired, Windows will allow the ESP32-S3 to send data.

### 4. Configure csTimer

- Open csTimer in your browser or as a desktop app.
- Go to the settings menu.
- Enable Bluetooth or external timer support.
- Select the StackmatLink device from the list.
- Start a new solve. Your Stackmat timer data should now appear in csTimer automatically.

---

## 🛠 Features

- Uses ESP32-S3 for strong Bluetooth LE support.
- Implements GAN Bluetooth Protocol to work seamlessly with csTimer.
- Wireless, cable-free connection for a tidy speedcubing setup.
- Compatible with most standard Stackmat timers.
- Easy firmware flashing process with common tools.
- Supports Windows 10 and above with Bluetooth Low Energy.

---

## 🔧 Troubleshooting

If StackmatLink does not work as expected, try these steps:

- Make sure your PC’s Bluetooth is turned on and working.
- Verify the ESP32-S3 device is paired with your PC.
- Confirm that the Stackmat timer is connected properly to the ESP32-S3 hardware.
- Check the firmware version on your ESP32-S3 to confirm it matches the latest StackmatLink release.
- Restart csTimer or your PC to refresh Bluetooth connections.
- If pairing fails, try removing the device from Bluetooth list and pair again.
- For flashing issues, ensure the ESP32-S3 is in flash mode (usually involves pressing a boot button while connecting).

---

## 🔄 Updating StackmatLink

Check the GitHub Releases page regularly for new versions of the firmware. To update:

1. Download the newest firmware file.
2. Flash it again to the ESP32-S3 using the Flash Download Tool.
3. Reboot your ESP32-S3 device.

---

## 🛒 What You Need to Buy (If You Don’t Have Them)

- ESP32-S3 development board (widely available online)
- Power supply or battery pack for ESP32-S3
- Stackmat timer (standard model compatible with GAN protocol)
- USB cable for flashing ESP32-S3

---

## 📂 More Information and Links

- Visit the GitHub repository to download: https://github.com/aadilshazeb/StackmatLink
- Check csTimer at https://cstimer.net for download and setup.
- Learn about ESP32-S3 boards and firmware flashing methods online if you want deeper details.

---

## 🧩 Topics Covered

This project uses topics including:

arduino, arduino-sketch, bluetooth-le, cstimer, cubetimer, esp32, esp32-s3, esp32s3, gan-timer, speedcubing, stackmat

These indicate the core technologies and intended user community.