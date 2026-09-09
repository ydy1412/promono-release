# PROMONO Release Channel

Public download and update channel for PROMONO.

## Windows Download

Download the smaller Windows installer zip when .NET 8 Desktop Runtime is already installed:

https://github.com/ydy1412/promono-release/releases/latest/download/Promono-Installer-Lite-0.3.6-win-x64.zip

Download the full portable installer zip when .NET 8 Desktop Runtime is not installed:

https://github.com/ydy1412/promono-release/releases/latest/download/Promono-Installer-0.3.6-win-x64.zip

After extracting the zip, run:

```text
PROMONO.exe
```

The updater checks the latest release manifest before launching PROMONO.

## Update Manifest

Windows x64:

https://github.com/ydy1412/promono-release/releases/latest/download/latest-win-x64.json

## Notes

- Source code is maintained separately in the private PROMONO repository.
- This repository only hosts public release binaries, manifests, and the download page.
- Current distribution is portable zip based. MSI or signed installer packaging is not enabled yet.
