# OS-W-CNF

>[!warning] ANOTHER ED IS REQUIRED

## Quick Start 

### Install

- Shift + F10
- `OOBE\BYPASSNRO`
- `ipconfig /release`

### Initial preparation

```
slmgr/ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
```
```
slmgr /skms kms.digiboy.ir
```
```
slmgr /ato
```
```
iwr -useb https://git.io/debloat|iex
```

> [!NOTE] checklist
> - [ ] Enable Restore Points
> - [ ] [ShutUp10++](https://www.oo-software.com/en/shutup10)
> - [ ] [Bloatynosy](https://github.com/builtbybel/BloatynosyAI/releases/tag/1.5.0)
> - [ ] [XToolBox](https://github.com/xemulat/XToolbox/releases/latest)
> - [ ] Enable Bitlocker
> - [ ] Create DPTN0 FSTC
> - [ ] Disable Windows Defender
> - [ ] Update Windows
> - [ ] Update applications by using Microsoft Store

### Installing applications

| nessesary                                                     | usability                                                                                                      | specific                                                            | system                                                               |
| ------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | -------------------------------------------------------------------- |
| [Google Chrome](https://www.google.com/chrome/)               | [Telegram](https://desktop.telegram.org/)                                                                      | [Parabolic](https://github.com/NickvisionApps/Parabolic/releases)   | [Squirrel Disk](https://github.com/adileo/squirreldisk/releases)     |
| [VeraCrypt](https://veracrypt.eu/en/Downloads.html)           | [Espanso](https://github.com/federico-terzi/espanso/releases/download/v2.1.8/Espanso-Win-Installer-x86_64.exe) | [Tagger](https://github.com/NickvisionApps/Tagger/releases)         | [Quick Look](https://github.com/QL-Win/QuickLook/releases/latest)    |
| [SyncTrazor](https://github.com/canton7/SyncTrayzor/releases) | [Microsoft Powertoys](https://apps.microsoft.com/detail/XP89DCGQ3K6VLD?hl=en-au&gl=US)                         | [PDF Arranger](https://github.com/pdfarranger/pdfarranger/releases) | [Everything](https://www.voidtools.com/downloads/)                   |
| [Obsidian](https://obsidian.md/download)                      | [Rnote](https://github.com/flxzt/rnote/)                                                                       |                                                                     | [Hone](https://www.mediafire.com/file/xdwb4zutkgd31tq/Hone.zip/file) |
| [Okular](https://apps.microsoft.com/detail/9n41msq1wnm8)      |                                                                                                                |                                                                     |                                                                      |
| [Xodo](https://apps.microsoft.com/detail/9wzdncrdjxp4)        |                                                                                                                |                                                                     |                                                                      |

### Applications configuring

> [!note] checklist
> - [ ] PS-I-V
> - [ ] PS-S
> - [ ] PS-O
> - [ ] PS-T
> - [ ] Espanso [base](https://github.com/SokolovskyMaxim/backup-configuration-files/blob/main/espanso)
> - [ ] PS-M-PT

### Configuring the registry

[powersettings](https://www.mediafire.com/file/ksr24q4zjb3y3tl/powersettings.reg/file)
[powerthrottling](https://www.mediafire.com/file/w8mzlgfjl97kmah/powerthrottling.reg/file)

## Resource-intensive setup  

```
wsl --install -d openSUSE-Leap-15.5
```

- [VSC](https://apps.microsoft.com/detail/xp9khm4bk9fz7q) [msys2](https://www.msys2.org/)
