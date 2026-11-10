# BT File Explorer

Native Android file manager by Benighter. Android 11 or later. This repository contains only signed downloads, checksums, update information and release notes. Application source and signing material are private.

[Download BT File Explorer 1.0.4](https://github.com/Benighter/bt-file-explorer-releases/releases/download/v1.0.4/BT-File-Explorer-1.0.4.apk) · [Release notes](https://github.com/Benighter/bt-file-explorer-releases/releases/tag/v1.0.4)

BT checks for updates when opened and from Settings. Automatic downloads show a progress bar. Android asks before installing an update; files and settings remain in place.

The application verifies the package identity, version, size, SHA-256 and preserved signing certificate before installation. Its update manifest is [`update.json`](update.json).

This directly distributed preview is not yet on Google Play. External SMB/SFTP/FTPS accounts and DLNA renderers still need endpoint testing. Android controls access to protected folders.

External Android/data and Android/obb access uses an explicitly authorized Shizuku connection. Start Shizuku again after a phone reboot. Affected MediaTek phones need the official Shizuku 13.5.4 release; private internal app and system files remain protected.
