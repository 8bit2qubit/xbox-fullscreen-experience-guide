# Guide: Upgrading to a Windows 11 Dev Build and Enabling the Xbox Fullscreen Experience

> 🌐 **English** | [繁體中文](README.zh-TW.md) | [简体中文](README.zh-CN.md)

<p align="center">
<a href="#"><img src="https://img.shields.io/badge/guide_version-0.0.2-blue.svg" alt="Guide Version"></a>
<a href="#"><img src="https://img.shields.io/badge/platform-Windows%2011%2026220.6690%2B-blueviolet.svg" alt="Platform"></a>
<a href="#"><img src="https://img.shields.io/badge/status-active-brightgreen.svg" alt="Status"></a>
</p>

This guide details the complete process for joining the Windows Insider Program, upgrading to the required Dev Channel build (Build 26220.6690+), and enabling the hidden Xbox fullscreen gaming experience.

### ⚠️ **Warning: Please Read Before Proceeding**

By proceeding with this guide, you acknowledge and agree to the following:

* **System Modification** – The procedures in this guide perform deep modifications to Windows and may cause system instability, crashes, data loss, or require a complete OS reinstallation.
* **Use at Your Own Risk** – You are fully responsible for any and all consequences. The developer and guide author provide no warranty, support, or liability for any damages incurred.
* **Backup Required** – You must back up all important data and create a system restore point before proceeding.
* **Unofficial Guide and Tool** – This guide and the associated tools are not affiliated with, endorsed by, or supported by Microsoft or Xbox.

---

### Step 1: Upgrade to Windows 11 Dev Channel Build (26220.6690+)

Enabling the Xbox fullscreen experience requires a specific Dev Channel build or newer.

#### 1. Understand the Dev Channel Commitment

Joining the Dev Channel is a significant technical commitment. Builds in the Dev Channel are often unstable. The only supported method to revert to a stable build is a clean installation of Windows, which will erase all data on the installation drive. Opting out of the program via Settings will not roll back your system to a stable version.

#### 2. Join the Windows Insider Program

* Navigate to the official [Windows Insider Program website](https://insider.windows.com/). Sign in with your Microsoft account to register and accept the program agreement.
* On your Windows 11 PC, open **Settings** and navigate to **Windows Update** > **Windows Insider Program**.
* Click **Get started** and link your registered Microsoft account.

#### 3. Switch to the Dev Channel and Initiate Upgrade

* When prompted to choose a channel, select **Dev Channel**.
* Acknowledge the risk warnings and restart your computer when prompted.
* After restarting, navigate to **Settings** > **Windows Update** and click **Check for updates**.
* The system will begin to download and install the latest Dev Channel build. This process can be lengthy and may require multiple restarts.

#### 4. Verify Your System Build

Once the update is complete, verify your OS build by navigating to **Settings** > **System** > **About**. Confirm that the **OS build** is `26220.6690` or higher.

---

### Step 2: Enable the Hidden Xbox Fullscreen Experience

Proceed with these steps once your system meets the build requirements.

#### 1. Download the Tool

Download the latest `.msi` installer from the [**Xbox Fullscreen Experience Tool releases page**](https://github.com/8bit2qubit/XboxFullscreenExperienceTool/releases/latest).

#### 2. Install the Tool

Execute the downloaded installer. Administrator privileges are required; follow the on-screen prompts to complete the installation.

#### 3. Run the Activation Process

* Launch the "Xbox Fullscreen Experience Tool" from its desktop shortcut.
* Click the **Enable Xbox Fullscreen Experience** button in the application's main window.
* **Restart** your computer as prompted to apply the changes.

#### 4. Restoration Process

To revert these changes, launch the tool, click the **Disable & Restore** button, and **restart** your computer.