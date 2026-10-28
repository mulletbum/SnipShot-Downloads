# SnipShot Downloads

Windows installer downloads and release notes for SnipShot, a screen capture and annotation tool.

## Release status

The first installer is being prepared for release. A Store-ready download will be published after code signing is configured. Draft releases are visible only to repository collaborators.

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
