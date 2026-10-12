# Atrium releases

Windows downloads for Atrium, a worship and media presentation application.

## Install

Download **Atrium-0.1.11-x64-setup.exe** from the [latest release](https://github.com/jerdonlee/atrium-releases/releases/latest). The rounded charcoal/gold setup defaults to `C:\Program Files\Atrium`, includes the runtime, content library and 16 background videos, and creates a Start menu shortcut. Backgrounds appear in **Media → Backgrounds** as Built-in.

The smaller **Atrium-0.1.11-x64.msi** is an application-only compatibility update for older updaters. It excludes background videos; use the full setup to get them.

## Update

In Atrium, open **Settings → Check for updates**. Downloads are verified with SHA-256 before installation. Your settings and services remain in your user folders. For 0.1.11, older updaters receive the small compatibility MSI because they have a 1 GB limit. If Windows Installer reports error 1619 from its cache, run the full setup manually.

Each release includes `latest.json` for update detection and `SHA256SUMS.txt` for independent verification.

## Support

Open **Settings → Support the developer → Buy me a coffee** to scan Noirfolk's GCash QR for an optional donation.

This repository distributes releases only. Application source is maintained in a separate private repository. PDF import and live native PowerPoint mirroring remain under development.
