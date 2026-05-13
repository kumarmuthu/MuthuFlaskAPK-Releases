# MuthuFlaskAPK

MuthuFlaskAPK is a unique Android application that hosts a local **Flask Web Server** directly on your mobile device. Leveraging **Chaquopy**, it runs a full Python environment natively, enabling powerful automation, media processing, and data management capabilities without needing a cloud backend.

## 🚀 Features

- **Local Python Server**: Integrated Flask server (Waitress) running on `127.0.0.1:5000`.
- **Advanced Automation**: Built-in support for Selenium, Paramiko, and pexpect.
- **Media & AI**: OpenCV, Pillow, and OpenAI integration.
- **Secure Storage**: Encrypted ZIP and credential management.
- **Dynamic Extensions**: Ability to upload and run custom Python dashboards and tools.

## 📥 How to Download and Install

Since this is a private project, the APK is hosted in this repository's **Releases** section.

1. **Download**: Navigate to the [Releases](https://github.com/muthu-scripts/MuthuFlaskAPK-Releases/releases) page.
2. **Select Version**: Download the latest `MuthuFlaskAPK.apk` file.
3. **Transfer**: If you downloaded it on a PC, transfer the APK to your Android device via USB or a cloud service.
4. **Enable Unknown Sources**:
   - Go to **Settings > Security** (or **Settings > Apps > Special app access**).
   - Enable **Install unknown apps** for your browser or file manager.
5. **Install**: Tap the APK file and follow the on-screen instructions to install.

## 🛠️ How to Use

1. **Launch**: Open the **Muthu Flask** app from your app drawer.
2. **Dashboard**: The app will automatically start the internal Flask server. The main screen displays the local dashboard.
3. **Server Info**: Click **"System Info"** on the home screen to verify the Python version and server status.
4. **External Access**: While the server defaults to `127.0.0.1`, internal services may be configured to communicate with other network components or cloud APIs (OpenAI/Firebase).
5. **Custom Apps**: Use the top-right menu (⋮) to upload or manage additional Python-based dashboards (e.g., GoldDashboard, MuthuMediaPlayer).
6. **GitHub Integration**: Clone public repositories (e.g., **MuthuAutomationWeb**) directly to add new features or dashboards as custom apps.

## 🔒 Security Note

- **Private Project**: This application is intended for private use.
- **Permissions**: The app requires File Storage and Network permissions to manage internal data and host the server.
- **Encryption**: Built-in scripts ensure that sensitive assets are protected via password-encrypted ZIP files during build time.

---
Developed with ❤️ by **Muthukumar S** | 2026
