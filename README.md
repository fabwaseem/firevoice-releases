# FireVoice

Natural voices, made on your own computer. FireVoice turns text into expressive speech, clones and designs voices,
changes voices, dubs, transcribes and makes music and sound effects, all locally on your GPU.

This repository holds the **installers and updates** only.

## Download

Get the latest version from **[Releases](https://github.com/fabwaseem/firevoice-releases/releases/latest)**:

- `FireVoice_<version>_x64-setup.exe`: the installer (recommended)
- `FireVoice_<version>_x64_en-US.msi`: the same app as an MSI package

## What you need

- Windows 10 or 11, 64-bit
- An NVIDIA graphics card is strongly recommended (the voice engines run on its CUDA cores)
- An internet connection for the first start: FireVoice sets up its voice engine once (a few GB)
- Free disk space for the engines you choose to install (each engine's size is shown before it downloads)

## Updates

FireVoice keeps itself up to date. When you are online and a new version is out, it downloads and installs it on
start, then opens the new version; your voices, history and settings stay as they are. Offline, it opens as usual.

Every update is signed, and FireVoice refuses to install one whose signature does not match. Each release also lists
the SHA-256 of its installers in `SHA256SUMS.txt`.
