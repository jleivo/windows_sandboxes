# Windows sandboxes
ref: https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-sandbox/windows-sandbox-overview \
Definitions for my various Windows Sandboxes

- zoom_box.wsb
  - A box for joining Zoom meetings to avoid installing Zoom on host
  - has video input enabled

- downloader.wsb
  - a box for downloading stuff with unauthorized tools, like utorrent
  - mounts c:\temp with write access

- tmp_installer.wsb
  - a box for testing various installations
  - mounts c:\temp with read permissions to Downloads -folder
  - starts explorer in the Downloads folder
