# From Scratch: A Complete Guide to Upgrading to Win11 Dev Build and Enabling the Xbox Fullscreen Gaming Experience

> 🌐 [繁體中文](README.zh-TW.md)

This guide provides a complete workflow, starting from joining the Windows Insider Program, upgrading your system to the required Developer Preview Build (Build 26220.6690+), and finally, successfully enabling the hidden Xbox fullscreen gaming experience.

### ⚠️ WARNING: READ BEFORE YOU PROCEED

By following any steps in this guide, you acknowledge that you have read, understood, and agreed to all the following terms:

* **High-Risk Operations**: Both upgrading to a Developer Preview Build and using third-party tools to modify your system are high-risk operations. These actions could lead to system crashes, application conflicts, data loss, or the need to reinstall your operating system.
* **At Your Own Risk**: You agree to assume **full responsibility for all potential consequences**, positive or negative. The developer and the author of this guide are not liable for any form of damage and offer no support.
* **Backup is Your Responsibility**: Before you begin, it is your responsibility to **create a full backup of all important data** and **create a system restore point**.
* **Unofficial Process**: The "Xbox Fullscreen Experience Tool" mentioned in this guide is is not affiliated with Microsoft or Xbox.

---

### Step 1: Upgrade to Windows 11 Developer Preview Build (26220.6690+)

To enable the Xbox fullscreen experience, your PC must be running a specific Developer Preview Build or newer.

#### 1. Understand the Dev Channel

First, you must understand that joining the Dev Channel is a significant technical commitment. Because its build numbers are typically far ahead of the stable version, **the only reliable way to exit is by performing a "clean install,"** which will erase all your data. Simply opting out of the program in Settings will leave you on the current unstable build; it will not revert you to the stable version.

#### 2. Join the Windows Insider Program

* Go to the official Windows Insider Program website, sign in with your Microsoft account to register, and accept the program agreement.
* Once registered, open the "Settings" app on your Windows 11 PC, navigate to "Windows Update" > "Windows Insider Program."
* Click "Get started" and link the Microsoft account you just registered.

#### 3. Switch to the Dev Channel and Upgrade

* On the channel selection screen, be sure to choose "Dev Channel."
* Acknowledge the risk warning that appears, then restart your computer.
* After rebooting, go back to "Settings" > "Windows Update" and click "Check for updates."
* The system will then download and install the latest Dev Channel build. Please be patient as this process may take some time and require several restarts.

#### 4. Verify Your System Build

After the installation is complete, you can go to "Settings" > "System" > "About" to confirm that your "OS build" is `26220.6690` or a newer version.

---

### Step 2: Enable the Hidden Xbox Fullscreen Experience

Once your system meets the version requirements, you can proceed to enable the feature.

#### 1. Download the Tool

Go to the [**Xbox Fullscreen Experience Tool releases page**](https://github.com/8bit2qubit/XboxFullscreenExperienceTool/releases/latest) to download the latest `.msi` installer file.

#### 2. Install the Tool

Run the installer you just downloaded. This process requires administrator privileges, so please follow the prompts to complete the installation.

#### 3. Run the Activation Process

* Launch the "Xbox Fullscreen Experience Tool" from your desktop shortcut.
* On the tool's main screen, click the "Enable Xbox Fullscreen Experience" button.
* As prompted by the tool, **restart** your computer to apply all changes.

#### 4. Restoration Process

If you wish to revert to the original state, simply run the tool again, click the "Disable & Restore" button, and **restart** your computer.