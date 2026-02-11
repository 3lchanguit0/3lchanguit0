# 3𝖑𝖈𝖍𝖆𝖓𝖌𝖚𝖎𝖙0

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

<div align="center">

![elchanguito](https://github.com/user-attachments/assets/848eefb3-c6a7-4fb7-893f-a881ea70b01c)

</div>

**3𝖑𝖈𝖍𝖆𝖓𝖌𝖚𝖎𝖙0** is a centralized security tool management terminal and pentesting dashboard designed for **Kali Linux**. It combines powerful offensive security tools into a simple minimalist interface using the **GNOME Desktop Environment**. Your computer is now a hacking gadget!

---

<div align="center">
  
🚧 𝐖𝐨𝐫𝐤 𝐈𝐧 𝐏𝐫𝐨𝐠𝐫𝐞𝐬𝐬 (𝐖𝐈𝐏) 

</div>

---

## 🚀 𝐒𝐲𝐬𝐭𝐞𝐦 𝐅𝐞𝐚𝐭𝐮𝐫𝐞𝐬

## 🛠 𝐀𝐩𝐩𝐥𝐢𝐜𝐚𝐭𝐢𝐨𝐧 𝐓𝐨𝐨𝐥𝐬 (𝐀𝐫𝐬𝐞𝐧𝐚𝐥)

The **TOOLS** suite is the core of 3lchanguit0, categorizing capabilities across the wireless spectrum to ensure you have the right tool for every frequency.

### 📶 𝐖𝐈-𝐅𝐈 (𝟖𝟎𝟐.𝟏𝟏)
Dominate the 2.4GHz spectrum with standard auditing and attack tools.
- **Deauthentication**: Forcefully disconnect clients from Access Points to capture handshakes.
- **Beacon Spam**: Generate thousands of fake Access Points to confuse scanners and decloak hidden networks.
- **PMKID Capture**: Harvest PMKID from APs for offline hash cracking.
- **Captive Portal**: Deploy phishing login pages for credential harvesting (Evil Twin attacks).
- **Hidden SSID**: Broadcast invisible networks for stealth operations.

### 🦷 𝐁𝐋𝐄 (𝐁𝐥𝐮𝐞𝐭𝐨𝐨𝐭𝐡 𝐋𝐨𝐰 𝐄𝐧𝐞𝐫𝐠𝐲)
Interact with the growing world of IoT and mobile devices.
- **BLE Spammer**: Flood advertisements to test the stability of nearby iOS/Android devices ("Sour Apple" attacks).
- **BLE Sniffer**: Detect, log, and analyze nearby Bluetooth Low Energy peripherals and trackers.

### 📡 𝐂𝐂𝟏𝟏𝟎𝟏 & 𝐍𝐑𝐅𝟐𝟒 (𝐒𝐮𝐛-𝐆𝐇𝐳)
Expand your reach beyond Wi-Fi into RF and proprietary protocols.
- **Sub-GHz Jamming**: Interfere with signals in the 433MHz, 868MHz, and 915MHz bands.
- **Spectrum Analyzer**: Visualize RF density to detect hidden transmitters or interference.
- **MouseJacking**: Inject keystrokes into vulnerable wireless mice and keyboards.
- **Replay Attack**: Record and retransmit RF signals (e.g., garage doors, gates).

### 📺 𝐈𝐑 (𝐈𝐧𝐟𝐫𝐚𝐫𝐞𝐝)
Control legacy hardware and consumer electronics via optical signals.
- **TV-B-Gone**: Universal power-off codes for turning off displays in public spaces.
- **IR Cloning**: Copy remote controls for later playback.
- **Brute Force**: Cycle through known codes to find the correct signal for a target device.

### ⚙️ 𝐒𝐘𝐒 / 𝐓𝐇𝐄𝐌𝐄
System-level utilities for hardware management and stealth.
- **Stealth Mode**: Instantly disable all LEDs and screens for covert operation.
- **Payload Delivery**: Emulate USB HID devices to execute scripts rapidly (Rubber Ducky style).
- **OTA Updates**: Wireless firmware flashing and management.

---

### 🖥️ 𝐊𝐚𝐥𝐢 𝐆𝐍𝐎𝐌𝐄 𝐈𝐧𝐭𝐞𝐫𝐟𝐚𝐜𝐞
3lchanguit0 gives a comprehensive UI and a specialized workspace for hardware hacking.
- **GNOME Shell Layout**: Left Dock (Dash) for quick application launching.
- **Terminal Integration**: A dedicated `root@kali:~` command-line interface for system logging, simulated command execution, and status feedback.
- **Activities Overview**: Streamlined workflow management designed for rapid tool switching during engagements.

---

## 💻 𝐑𝐞𝐪𝐮𝐢𝐫𝐞𝐦𝐞𝐧𝐭𝐬

To ensure optimal performance and compatibility, the following environment is recommended:

### 𝐒𝐨𝐟𝐭𝐰𝐚𝐫𝐞
- **Operating System**: Kali Linux 2023.x or newer (Recommended for native tool integration).
- **Runtime**: Node.js v16.0.0 or higher.
- **Package Manager**: npm (v8+) or yarn.
- **Browser**: Chromium-based browser (Chrome, Brave, Edge) with WebSerial API support for flashing features.

### 𝐇𝐚𝐫𝐝𝐰𝐚𝐫𝐞 𝐒𝐮𝐩𝐩𝐨𝐫𝐭
The firmware management suite supports the following chipsets and boards:
- **Espressif**: ESP32 WROOM, ESP32 WROVER.
- **M5Stack**: M5StickC, M5StickC Plus, M5StickC Plus 2, Cardputer.
- **Peripherals** (Optional): 
  - CC1101 Transceiver (for Sub-GHz).
  - NRF24L01 (for 2.4GHz sniffing).
  - IR Blaster (Built-in on M5Stick).

### ⚠️ 𝐈𝐦𝐩𝐨𝐫𝐭𝐚𝐧𝐭!
**To use some of the features you will need one of the ESP32 mentioned above. 3lchanguit0 must be flashed on your ESP32.**
**I'm currently working on the flasher and the `.bin`**

---

## 📂 𝐂𝐫𝐞𝐝𝐢𝐭𝐬 & 𝐅𝐢𝐫𝐦𝐰𝐚𝐫𝐞 𝐒𝐨𝐮𝐫𝐜𝐞𝐬

- **[3lchanguit0](https://github.com/3lchanguit0)** manages the following open-source projects.
- **SYS_ALPHA**: based on [BruceDevices Firmware](https://github.com/BruceDevices/firmware)
- **UNIT_ZERO**: based on [M5Stick-Nemo](https://github.com/n0xa/m5stick-nemo)
- **GHOST_PROTOCOL**: based on [Infiltra-Firmware](https://github.com/D3CRYPT-1/Infiltra-Firmware)
- **OMEGA_CORE**: based on [ESP32Marauder](https://github.com/justcallmekoko/ESP32Marauder)

---

## 🛠 𝐈𝐧𝐬𝐭𝐚𝐥𝐥𝐚𝐭𝐢𝐨𝐧

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/3lchanguit0.git
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm run dev
   ```

---

## ⚠️ 𝐃𝐢𝐬𝐜𝐥𝐚𝐢𝐦𝐞𝐫

**Authorized Use Only.**
This software is intended for educational purposes and authorized security auditing only. 3lchanguit0 assumes no liability for misuse of this software or the firmware projects it references. Ensure you have explicit permission from the owner of any network or device you test. Use it responsibly and within the boundaries of your country laws.

---

## 📄 𝐋𝐢𝐜𝐞𝐧𝐬𝐞

MIT License
