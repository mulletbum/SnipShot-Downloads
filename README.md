# SnipShot Downloads

Windows installer downloads and release notes for SnipShot, a screen capture and annotation tool.

## Release status

An [unsigned preview installer](https://github.com/mulletbum/SnipShot-Downloads/releases/download/v1.6.0-unsigned-preview/SnipShot-1.6.0-x64.msi) is available for testing. Windows may show an Unknown publisher or SmartScreen warning. This preview is not ready for Microsoft Store submission. A signed release will use a separate versioned URL.

## System requirements

- 64-bit Windows 10 or Windows 11
- .NET Framework 4.8 or newer

## Installation

Download the MSI from this repository's Releases page, install it, then launch SnipShot from the Start menu. Installers run for the current Windows user and include an uninstall entry in Windows Installed apps.

For unattended installation, use:

```powershell
msiexec /i "SnipShot-1.6.0-x64.msi" /qn /norestart
```

## Capture shortcuts

The default capture shortcut is Ctrl + 1. Open SnipShot and select Capture hotkey > Change hotkey to choose your own combination or Print Screen.

## Release integrity

Each published installer version has its own download URL and SHA-256 checksum. Use the version-specific link when distributing an installer. This repository contains download documentation and release assets; application source code is maintained separately.
