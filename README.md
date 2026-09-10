# PROMONO Release Channel

Public download and update channel for PROMONO.

## Windows Download

Download the Windows setup executable:

https://github.com/ydy1412/promono-release/releases/latest/download/PROMONO-Setup-0.3.10-win-x64.exe

The setup executable downloads the latest full package, installs it under the
user's local app data folder, creates a desktop shortcut, and starts PROMONO.

Manual zip fallback:

https://github.com/ydy1412/promono-release/releases/latest/download/Promono-Installer-0.3.10-win-x64.zip

After manual extraction, run:

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
- Current distribution uses an unsigned setup executable plus manual zip fallbacks. MSI or signed installer packaging is not enabled yet.
