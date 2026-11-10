<p align="center">
  <img src="assets/logo.svg" width="96" height="96" alt="FireVoice logo">
</p>

<h1 align="center">FireVoice</h1>

<p align="center">
  <b>Natural voices, made on your own computer.</b><br>
  Expressive text to speech, voice cloning and design, dialogue, dubbing, transcription, music and sound effects,
  all running locally on your GPU.
</p>

<p align="center">
  <a href="https://github.com/fabwaseem/firevoice-releases/releases/latest"><b>Download for Windows</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/fabwaseem/firevoice-releases/releases">All releases</a>
</p>

<p align="center">
  <img src="assets/screenshots/speak.webp" alt="FireVoice Speak: write a script, pick a voice and a delivery, render it on your GPU" width="100%">
</p>

## A look inside

<table>
  <tr>
    <td width="50%"><img src="assets/screenshots/voices.webp" alt="Voice library with 100 voices"><br><b>Voices</b>: a library of 100 voices, plus your own clones and voices designed from a description.</td>
    <td width="50%"><img src="assets/screenshots/dialogue.webp" alt="Dialogue editor with a cast of speakers"><br><b>Dialogue</b>: write "Name: line", cast a voice per speaker, get one mix and a track per speaker.</td>
  </tr>
  <tr>
    <td width="50%"><img src="assets/screenshots/tools.webp" alt="Audio tools"><br><b>Tools</b>: pull a voice out of music, score a recording's quality, check for AI speech.</td>
    <td width="50%"><img src="assets/screenshots/sound.webp" alt="Sound effects and music from a description"><br><b>Sound</b>: sound effects, ambience and music beds from a description.</td>
  </tr>
  <tr>
    <td colspan="2"><img src="assets/screenshots/engines.webp" alt="Voice engines"><br><b>Engines</b>: choose the voice engine that fits: studio quality, fast, small, many languages. Install only what you use.</td>
  </tr>
</table>

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
