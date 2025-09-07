
# Dhanu - Installer-ready package (Windows)

This package is prepared so you can build the final installer locally on your Windows machine with one script.
I cannot create the signed Setup.exe inside this environment, but this folder includes everything needed to produce the installer using electron-builder on Windows.

## Quick steps (one-shot on your Windows PC)
1. Extract this zip to a folder, e.g. `C:\Users\<you>\Downloads\dhanu_installer_ready`
2. Open PowerShell **as Administrator** (recommended).
3. Run:
   ```powershell
   cd "C:\Users\<you>\Downloads\dhanu_installer_ready"
   .\build_installer_windows.ps1
   ```
4. If Node is not installed, the script will prompt you to install it. After installing Node, re-run the script.
5. The produced `Dhanu Setup.exe` should appear in the project root (or see `dist/` folder).

## Notes
- Building requires internet to download npm packages and electron-builder dependencies.
- Building may take several minutes.
- If you want the installer uploaded somewhere, I can guide you to upload it to Google Drive or Dropbox once you have the Setup.exe.
