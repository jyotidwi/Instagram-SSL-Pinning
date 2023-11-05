# Instagram-SSL-Pinning 🚀
Bypass Instagram SSL pinning on Android x86.

- **APK Version:** Instagram_307.0.0.34.111.apk 🎯
- **Architecture:** x86 


## Table of Contents 📚

- Prerequisites
- Installation
- Configuration
- Usage
- Updates
- Support
- License


## Prerequisites 📋

Before you begin, ensure you have met the following requirements:
- A PC with internet access.
- Basic understanding of Android emulators and ADB (Android Debug Bridge).

## Installation 🛠️

### 1. **Download and Install Memu**
   - Visit [MEmuPlay](https://www.memuplay.com) to download and install Memu.
   - Follow the installation prompts to complete the setup.

### 2. **Create New Instance**
   - Launch Multi-MEmu on your PC.
   - Click on `Create` and select `Android 7.1` as the version.
   - Ensure to select `x86` architecture and name your instance accordingly.

### 3. **Enable Root Permission**
   - Once your instance is created, click on `Settings` (⚙️).
   - Go to `Settings` -> `Engine` and enable `Root` mode.

### 4. **Download Repository**
   - Click on the green `Code` button on this GitHub page and choose `Download ZIP`, or clone the repository using Git.
   - Extract the contents to your desired location.

### 5. **Install Instagram APK**
   - Locate the `Instagram_307.0.0.34.111.apk` file in the downloaded repository.
   - Drag and drop the APK file into the Memu instance to install.

### 6. **Install ADB Tools**
   - Download and install [ADB Tools](https://developer.android.com/studio/releases/platform-tools).
   - Place `libliger.so` in the adb directory.

## Configuration ⚙️

### 1. **Push libliger.so File**
   - Open a command prompt or terminal.
   - Navigate to the directory where `libliger.so` file is located (within theadb folder).
   - Launch Instagram once in MEmu, and then close it.
   - Execute the following command:
     ```bash
     adb push libliger.so /data/data/com.instagram.android/lib-compressed/libliger.so
     ```

### 2. **Setup Proxy Server**
   - Download and install BurpSuite.
   - Follow [these instructions](https://portswigger.net/burp/documentation/desktop/mobile/config-android-device) to set up a proxy server with BurpSuite.

## Usage 🚀

With everything set up, you are now ready to explore. Enjoy !

## Updates 🔄

For new updates, please send an email to tarun360@duck.com. I will try to provide updates as and when I have some free time.

## Support 💬

For any issues or queries, feel free to open an issue.

## License 📜

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License.
