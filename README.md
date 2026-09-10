# amd-driver-tools

Static assets used by an automated AMD GPU driver install script:

- `InstallManifest.json` — AMD's own driver package manifest (from a current
  AMD Software: Adrenalin Edition installer), listing package versions,
  download paths, and PCI hardware-ID match rules per package.
- `7za.exe` — official 7-Zip 26.03 "Extra" standalone console build
  ([7-zip.org](https://www.7-zip.org/), public domain / LGPL), used to
  extract AMD's self-extracting driver packages (PowerShell has no native
  7z support).

Both files are unmodified redistributions of public, vendor-provided content.
