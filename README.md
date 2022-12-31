# GenuineClient

Simple SPT-AKI crack method.

## Installation

1. Ensure your folder directory looks like this:

```
<gamedir>/
├─ EscapeFromTarkov_Data/
├─ GenuineClient/
│  ├─ BattlEye/
│  │  ├─ BEClient_x64.dll
│  ├─ ConsistencyInfo
│  ├─ Uninstall.exe
│  ├─ UnityCrashHandler64.exe
├─ MonoBleedingEdge/
├─ NLog/
├─ EscapeFromTarkov.exe
├─ UnityPlayer.dll
```

2. In registry, set `Computer\HKEY_LOCAL_MACHINE\Software\Wow6432Node\Microsoft\Windows\CurrentVersion\Uninstall\EscapeFromTarkov\UninstallString` to `<gamedir>\GenuineClient\Uninstall.exe`.
Create the key(s) if it doesn't exist yet.

## Notes

- The files in this repo are all hollow. In case you don't trust it, you can recreate these files yourself by creating a new text file without file extension, and rename it to the desired file.
