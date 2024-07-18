# OS-W zero configuring

>[!warning] ED-2 IS REQUIRED

## Install


> [!info] https://github.com/SokolovskyMaxim/configuration-files-backup/blob/main/OS-W-CNF.md

- [ ]  Shift + F10

```
oobe\bypassnro
```

```
ipconfig /release
```

## Initial preparation

```
slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
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

```
Get-AppxPackage -AllUsers | Where-Object {$_.Name -like "*WebExperience*"} | Remove-AppxPackage -AllUsers -ErrorAction SilentlyContinue
```

> [!todo]

- [ ] Enable Restore Points
- [ ] [ShutUp10++](https://www.oo-software.com/en/shutup10)
- [ ] [App Buster](https://www.oo-software.com/en/ooappbuster)
- [ ] [Bloatynosy](https://github.com/builtbybel/Winpilot/releases/tag/1.5.0)
- [ ] Disable Windows Defender (gpedit)
- [ ] Update Windows
- [ ] Enable Bitlocker
- [ ] Create DPTN0 FSTC

## Installing nessesary PS

> [!todo]

- [ ] [VeraCrypt](https://veracrypt.eu/en/Downloads.html)
- [ ] [Obsidian](https://obsidian.md/download)
- [ ] [Syncthing](https://github.com/syncthing/syncthing/releases/latest)

## DAL1 data recovery + necessary PS configuring

```
wsl --install -d openSUSE-Leap-15.5
```

>[!todo]

- [ ] PS-V
- [ ] `wsl`
- [ ] `zypper in openssl`
- [ ] [[D1DEA#Decryption]]
- [ ] [PS-S](https://docs.syncthing.net/users/autostart.html#windows)
- [ ] PS-O
- [ ] KEY of Bitlocker
