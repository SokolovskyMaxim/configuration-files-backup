---
version: 1.0-rc
---
# DEPL_ENV_W

## Action Sequence

### Section 1: ISO installation

**1/** Select the boot device in the BIOS. Boot from the USB drive. Choose the installation option without entering the key initially

**2/** Press `Shift + F10` in the language selection menu

```
oobe\bypassnro
ipconfig /release
```

**3/ User account, keyboard layouts.** Enter the credentials for the corresponding ED, add RU keyboard layout

### Section 2

**1/ Activate OS-W.** Execute the first two commands, then access the Internet and execute the third

```
slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
slmgr /skms kms.digiboy.ir
slmgr /ato
```

**2/** 

- [ ] Update OS-W and drivers
- [ ] Enable Restore Points

**3/ Remove bloatware.** Create a restore point before each program is executed

- [ ] `iwr -useb https://git.io/debloat|iex`
- [ ] [ShutUp10++](https://www.oo-software.com/en/shutup10)
- [ ] [Bloatynosy](https://github.com/builtbybel/Winpilot/releases/tag/1.5.0) 
- [ ] [App Buster](https://www.oo-software.com/en/ooappbuster) 
- [ ] `Get-AppxPackage *WebExperience* | Remove-AppxPackage `

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
- [ ] Install correct [audio driver](https://www.catalog.update.microsoft.com/Search.aspx?q=everest%20i2s%20codec%20audio%20device)

### Section 3: Download all application installation files and install all of them

- [ ] [Google Chrome](https://www.google.com/chrome/)
- [ ] [VeraCrypt](https://veracrypt.eu/en/Downloads.html)
- [ ] [Obsidian](https://obsidian.md/download)
- [ ] [Syncthing](https://github.com/syncthing/syncthing/releases/latest)
- [ ] [Python](https://www.python.org/downloads/windows/). Install for all users
- [ ] [VS Code](https://code.visualstudio.com/Download)
- [ ] [Telegram](https://desktop.telegram.org/)
- [ ] [Espanso](https://github.com/federico-terzi/espanso/releases/)
- [ ] [Quick Look](https://github.com/QL-Win/QuickLook/releases/latest)
- [ ] [Everything](https://www.voidtools.com/downloads/)
- [ ] [Git](https://git-scm.com/downloads/win)
- [ ] [VLC](https://www.videolan.org/vlc/download-windows.html)
- [ ] [ImageGlass](https://imageglass.org/release/download/imageglass-9-1-8-723-154)
- [ ] [Hiddify](https://github.com/hiddify/hiddify-next/releases/latest)
- [ ] [Syncthing CLI Tool](https://github.com/tenox7/stc/releases/latest)
- [ ] [SumatraPDF](https://www.sumatrapdfreader.org/download-free-pdf-viewer)
- [ ] `wsl --install`

### Section 4: Configure some system settings and critical applications, and make data available for further configuration

**1/ Set up SF-S-VC.**

- [ ] Create new vault DAL1
- [ ] Create DPTN0 FSTC
- [ ] Set up "favorites", set auto-editing at startup, set up keyboard shortcuts

**2/ Basic setup of SF-T-WL**

- [ ] Copy from ED-11, decrypt and unzip D1B
- [ ] Get full access to DAL1. Get access to configuration files in DAL1
- [ ] Import `wsl_backgound.xml` task from `$D1/lib/backup`

```
sudo apt update
sudo apt upgrade -y
sudo apt install zip openssl coreutils
```
