# 🔄 From Windows to Linux (Ubuntu)

This guide provides a step-by-step walkthrough for migrating from **Windows 10** to a **Linux-based operating system**, using **Ubuntu 24.04 LTS**. The focus is on safe data handling, understanding the boot process, and completing a clean Linux installation.

---

## 💻 Environments and Technologies Used

- **PC / Laptop**
- **External Flash Drive or External HDD** (boot media)
- **Optional:** Secondary storage device for backups

---

## 🖥️ Operating Systems Used

- **Windows 10**
- **Ubuntu 24.04.3 LTS**

---

## ✅ Prerequisites

Before starting, download and install the following:

- **Ubuntu Desktop (LTS ISO)**  
  https://ubuntu.com/download/desktop

- **Balena Etcher** (ISO flashing utility)  
  https://etcher.balena.io

> ⚠️ **Important:** Any flash drive used in this process will be **fully formatted**. Back up its contents beforehand.

---

## 🚀 Installation Steps

---

## 📥 Download Required Files

- **Ubuntu `.iso` file**  
  The Linux distribution image that will replace Windows upon installation.

- **Balena Etcher**  
  Used to flash the Ubuntu ISO to an external drive, allowing the system to boot via BIOS/UEFI.

---

## 💾 Back Up Your Data

Before making system-level changes:

- Back up **important personal files**
- Optionally create a **full Windows system backup**
- Ensure the flash drive used for installation is **empty**, as it will be reformatted

---

## 🔥 Create the Ubuntu Boot Drive

1. Insert your flash drive
2. Open **Balena Etcher**
3. Select **Flash from file**
4. Choose the downloaded **Ubuntu `.iso`**
5. Select the external drive as the target
6. Confirm and allow the flashing process to complete

---

## ⚙️ Boot into BIOS / UEFI

1. Shut down the computer (leave the flash drive plugged in)
2. Power on the system
3. Press your device’s **boot key** (`F2`, `F10`, or `F12`, depending on hardware)

Inside BIOS/UEFI:
- Navigate to the **Boot** section
- Set the external drive as the **first boot device**
- Save changes and exit (`F10`)

---

## 🧪 Launch Ubuntu Live Environment

- From the boot menu, select **Ubuntu (safe graphics)**
- The system loads into **Ubuntu Live Mode**
  - This is a temporary demo environment running from the flash drive
  - Slower performance is expected at this stage

---

## My Ubuntu Installation Recommendations

During the installer setup, it's all a matter of preference, but I recommend the following selections:

- **Interactive Installation**
- **Extended selection of applications**
- Enable:
  - *Install third-party software for graphics and Wi-Fi*
  - *Download and install support for additional media formats*
- **Erase disk and install Ubuntu**
- **Enable disk encryption**
  - Save the encryption passphrase! — it is required at boot

---

## Final Result

After installation completes and the system reboots:

✅ Windows has been fully replaced  
✅ Ubuntu 24.04 LTS is installed  
✅ System is now running on a Linux-based platform  
