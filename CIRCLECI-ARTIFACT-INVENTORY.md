# CircleCI Artifact Inventory — Release Candidate 087b974

Source: successful CircleCI release-preflight job 501.

## Full NI delivery artifact
CircleCI artifact group: `FullForceDAW-2.1.0-NI-delivery`

Confirmed contents:
- `FullForceDAW-2.1-Windows-x64-Setup.exe` — customer Windows installer
- `FullForceDAW-2.1.0-macOS-unsigned.pkg` — customer macOS package
- `NI-DELIVERY-CHECKLIST.txt`
- `NI-DELIVERY-MANIFEST.txt`
- `CUSTOMER-INSTALLERS-SHA256.txt`
- `QA-EVIDENCE/COMBINED-PREFLIGHT.txt`
- macOS: `MACOS-RELEASE-STATUS.txt`, `SHA256SUMS.txt`, `MACOS-HOST-QA.txt`, `PLUGINVAL-MACOS-CONSOLE.txt`, `BINARY-ARCHITECTURE.txt`, `MACOS-INSTALL-QA.txt`
- Windows: `BUILD-PROVENANCE.txt`, `FINAL-RELEASE-VERDICT.txt`, `INSTALL-QA.txt`, `PLUGINVAL-INSTALLER-CONSOLE.txt`, `REAPER-INSTALLER-QA.txt`, `SHA256SUMS.txt`, `REAPER-VISUAL-QA-CONSOLE.txt`, `STEINBERG-INSTALLER-QA.txt`

CircleCI reported total uploaded size: approximately 3.9 MiB.

## Evidence archive
`FullForceDAW-2.1.0-NI-delivery-evidence.tar.gz` — CircleCI reported approximately 18 kB.

## Release-preflight artifact
Artifact group: `NI-release-preflight`
- `PREFLIGHT.txt`
- `SHA256SUMS.txt`

## Important
The three files supplied to ChatGPT were CircleCI **upload-step logs**, not the binary artifacts themselves. They prove the names and successful artifact uploads but do not contain the .exe, .pkg, or evidence payload bytes. The exact CircleCI artifacts must be downloaded and uploaded here/repository without rebuilding them.
