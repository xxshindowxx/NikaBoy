# About NikaBoy

- current version: v0.6

- Open Source Project for an emulation device. A Project i came up myself and was suprised when i saw that a company even sold something like this way back(They are off the market).

- NikaBoy is a Project that emulates various games from GameBoy.
It can also emulate different Games with the right SBC.

## Supported Consoles

- GameBoy
- GameBoy Color
- GameBoy Advance
- Nintendo Entertaiment System
- Super Nintendo Entertaiment System
- Master System
- Game Gear
- PC Engine
- Atari 2600/5200
- Commodore 64
- Neo Geo

  ## License

This project is licensed under the [Creative Commons Attribution-Share Alike 4.0](https://creativecommons.org/licenses/by-sa/4.0/) license.

# Getting Started

## Prerequisites
- Raspberry Pi Zero 2 W
- 32GB Micro SD Card (V30 recommended)
- 3D Printer (or pre-printed case)
- USB Controller
- Basic soldering skills (optional, depending on assembly)

## Quick Steps

1. **Print the Case**
   - Download 3D models from [Hardware/3D Models](Hardware/3D%20Models/)
   - Print with ASA material
   - Estimated print time: ~8-12 hours

2. **Install Batocera**
   - Download Batocera for Pi Zero 2 W from [Batocera.org](https://batocera.org/download)
   - Flash to SD card using [Raspberry Pi Imager](https://www.raspberrypi.com/software/)
   - See [Software Guide](Software/README.md) for details

3. **Assemble the Device**
   - Place Pi Zero 2 W in case
   - Connect screen and controller
   - Add power bank
   - (Full assembly guide coming soon with pictures/video)

4. **Add Games**
   - Copy ROM files to SD card
   - Boot up and play!

## What's Next?
- Check [Contributing Guidelines](CONTRIBUTING.md) to improve the design
- Report issues or suggest improvements
- Join our community!

## Coming Soon! 
Assembly steps and video guide will be added once the prototype is complete.

For now, check:
- [Hardware Specs](README.md#hardware)
- [Software Setup](Software/README.md)

# Hardware

- Case: [3D Printed with ASA](https://cad.onshape.com/documents/dd91bae101324d5c429ef6cf/w/cb18bab8c2ce562646a1ddd5/e/844543bad99d799db881c0ff) or Direct download here [3D Models](Hardware/3D%20Models/)
  
  <img src="Images/NikaBoy%203D.png" width="200" alt="NikaBoy device">

- SBC: [Raspberry Zero 2 W](https://www.berrybase.de/raspberry-pi-zero-2-w)

  <img src="Images/RaspberryPiZero2W.webp" width="200" alt="NikaBoy device">
  
- Cooling: [Passiv Cooler from Waveshare](https://www.berrybase.de/waveshare-aluminiumkuehlkoerper-fuer-raspberry-pi-zero-zero-2-w)

  <img src="Images/WaveshareAluminiumkhlkrperfrRaspberryPiZeroZero2W.webp" width="200" alt="NikaBoy device">

- SD Car: [SanDisk 32Gb](https://www.berrybase.de/sandisk-ultra-microsdhc-a1-120mb-s-class-10-speicherkarte-adapter-32gb)

  <img src="Images/SanDiskExtrememicroSDHCA1UHS-IU3SpeicherkarteAdapter32GB.webp" width="200" alt="NikaBoy device">

- Powerbank: [INU Rocket Pocket(P50-E1)](https://eu-main.iniushop.com/de/products/new-colorful-iniu-carry-p50-e1-power-bank-45w-smallest-10000mah)

  <img src="Images/P50.webp" width="200" alt="NikaBoy device">

- Controller: [SNES Controller](https://www.berrybase.de/usb-2.0-controller-im-snes-design-grau)

  <img src="Images/USB20ControllerimSNESDesigngrau.webp" width="200" alt="NikaBoy device">
  
- Screen: [3.5 inch/Zoll LCD from Waveshare](https://www.waveshare.com/product/3.5inch-hdmi-lcd.htm)

  <img src="Images/3.5ap-m_2.jpg" width="200" alt="NikaBoy device">
  


# Software

- Since i used Batocera on a PC before i will use it on this project too.

- The boot/config.txt will be edited for better Performance with "Higher" demanding Consoles



# **DISCLAIMER**

- This project **contains** information and instructions for opening power banks and related devices. 

**Please note:**
- This project is for **educational purposes only**
- Opening devices may **void warranties**
- Improper handling can cause **injury or damage**
- Always follow **safety precautions** when working with batteries and electronics
- I am **not responsible** for any damage, injury, or loss resulting from the use of this information
- Check local laws and regulations before disassembling any devices

- You are free to use other Hardware and Software for this Project if you want. My current subtotal is 122€

**Use at your own risk.**
