# Cast-X: Android Screen Mirroring to Windows PC

Cast-X is a Windows application that enables seamless screen mirroring from Android devices to Windows PCs and laptops. Whether you're a developer, tech enthusiast, or simply someone who wants to mirror their Android screen, Cast-X provides an easy-to-use solution.

## Features

- **Efficient Mirroring**: Cast your Android screen to your Windows PC with minimal latency and smooth performance.
- **USB and Wireless Connectivity**: Choose between USB or wireless connection modes. For wireless mirroring, connect your Android device via USB initially, enable TCP/IP, and then enjoy wireless screen sharing.
- **Real-Time Interaction**: Control your Android phone directly from your Windows PC using Cast-X.
- **Multi-Device Support**: Connect and mirror multiple Android devices simultaneously.
- **Cross-Platform Compatibility**: Works seamlessly on Windows 10, 8, and 7.

## Getting Started

### Requirements

- Android 5.0 or later
- USB cable
- Enabled USB debugging on your Android device

### Installation

1. Download the latest release of Cast-X from the Releases page.
2. Extract the zip file to a convenient location on your PC.

### Usage

#### Wireless Connection

1. Connect your Android device via USB initially.
2. Enable TCP/IP on your device using the command:
   ```bash
   adb tcpip 5555
   ```
3. Disconnect the device and connect wirelessly using:
   ```bash
   adb connect <IP_ADDRESS>:5555
   ```
4. Run `Cast-X.exe` to start wireless screen mirroring.

#### USB Connection

1. Connect your Android device to your PC via USB.
2. Open the command prompt and run `Cast-X.exe`.

### Customization

- Adjust the screen resolution for performance optimization.
- Explore Cast-X’s various settings for a tailored experience.

## Contribution and Feedback

We welcome contributions to this project! If you encounter any issues or have suggestions, feel free to open an issue or submit a pull request on GitHub.

---

Happy screen mirroring! 📱💻
