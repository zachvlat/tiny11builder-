DISCLAIMER:
Although I include the oscdimg.exe file I highly urge you to download yourself and don't use the one I provide you, for security reasons.
Download The Windows ADK from this [link](https://learn.microsoft.com/en-us/windows-hardware/get-started/adk-install#download-the-adk-for-windows-11-version-22h2) and then, during the installation, choose only the Deployment Tools.

Also the installation of tiny11.iso must be happen OFFLINE

# Run it

1. Download this repository as zip and unzip it where you want.
2. Open a Powershell as administrator, go to the extraction path, and run the
   following commands and wait:

```
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.\tiny11creator.ps1
```

3. The created Windows 11 installer iso is available in c:\tiny11.iso

# Features

Removed apps: (except the forked ones)
Teams
WindowsCalculator
WindowsCamera
WindowsNotepad
Windows.Photos
WindowsStickyNotes (TODO)
WindowsTerminal
MSPaint (TODO)
WindowsStore
GetStarted (TODO)
