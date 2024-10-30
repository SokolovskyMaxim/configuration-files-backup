---
version: 1-alpha
---
# DEPL_OS_W

## Action Sequence

### Section 1: ISO installation

**1/** Select the boot device in the BIOS. Boot from the USB drive. Choose the installation option without entering the key initially

**2/** Press `Shift + F10` in the language selection menu

```
oobe\bypassnro
ipconfig /release
```

### Section 2

**1/ Activate OS-W**

```
slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
slmgr /skms kms.digiboy.ir
slmgr /ato
```

**2/** 

- [ ] Update OS-W and drivers
- [ ] Enable Restore Points

**3/ Remove bloatware**

- [ ] `iwr -useb https://git.io/debloat|iex`
- [ ] [ShutUp10++](https://www.oo-software.com/en/shutup10)
- [ ] [App Buster](https://www.oo-software.com/en/ooappbuster) 
- [ ] [Bloatynosy](https://github.com/builtbybel/Winpilot/releases/tag/1.5.0) 

**4/ Disable Windows Defender**

- [ ] Open `gpedit.msc`
- [ ] Go to `Computer Configuration` > `Administrative Templates` > `Windows Components` > `Microsoft Defender Antivirus`
- [ ] Set `Enabled` for `Turn off Microsoft Defender Antivirus`
- [ ] Disable Tamper Protection in `Windows Security`

**5/** 

- [ ] Enable `Bitlocker`
- [ ] Save encryption `KEY`
- [ ] Change hostname
- [ ] Change encoding to utf-8
- [ ] Disable most of visual effects, change swap size: `Settings`, `View advanced system settings`
- [ ] Add fingerprint (optional)

### Section 3: Download all application installation files

- [ ] [Google Chrome](https://www.google.com/chrome/)
- [ ] [VeraCrypt](https://veracrypt.eu/en/Downloads.html)
- [ ] [Obsidian](https://obsidian.md/download)
- [ ] [Syncthing](https://github.com/syncthing/syncthing/releases/latest)
- [ ] [Python](https://www.python.org/downloads/windows/)
- [ ] [VS Code](https://code.visualstudio.com/Download)
- [ ] [Telegram](https://desktop.telegram.org/)
- [ ] [Espanso](https://github.com/federico-terzi/espanso/releases/)
- [ ] [Quick Look](https://github.com/QL-Win/QuickLook/releases/latest)
- [ ] [Everything](https://www.voidtools.com/downloads/)
- [ ] [Git](https://git-scm.com/downloads/win)
- [ ] [VLC](https://www.videolan.org/vlc/download-windows.html)
- [ ] [Irfan View](https://www.irfanview.com/64bit.htm)
- [ ] [Hiddify](https://github.com/hiddify/hiddify-next/releases/latest)
- [ ] `wsl --install`

### Section 4: Configure some system settings and critical applications, and make data available for further configuration

**1/ Set up SF-S-VC.**

- [ ] Install app
- [ ] Create new vault DAL1
- [ ] Create DPTN0 FSTC

**2/ Basic setup of SF-T-WL**

- [ ] Copy from ED-11, decrypt and unzip D1B
- [ ] Get full access to DAL1. Get access to configuration files in DAL1

```
sudo apt update
sudo apt upgrade
sudo apt install zip openssl coreutils
```
