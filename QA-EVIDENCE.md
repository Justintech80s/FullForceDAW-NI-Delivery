# Full Force DAW QA Evidence

Release candidate: `087b974acc2ea741301691dfc4658149a8b0438c`

## CircleCI gates confirmed passing
- Web CI — PASS
- Native tests — PASS
- Windows VST3 — PASS
- NI Windows customer installer — PASS
- macOS VST3 — PASS
- Combined release preflight — PASS

## Windows evidence expected from frozen CircleCI artifacts
`FINAL-RELEASE-VERDICT.txt`, `BUILD-PROVENANCE.txt`, `INSTALL-QA.txt`, `STEINBERG-INSTALLER-QA.txt`, `PLUGINVAL-INSTALLER-CONSOLE.txt`, `REAPER-INSTALLER-QA.txt`, `REAPER-VISUAL-QA-CONSOLE.txt`, `SHA256SUMS.txt`.

## macOS evidence expected
`MACOS-RELEASE-STATUS.txt`, `MACOS-INSTALL-QA.txt`, `MACOS-HOST-QA.txt`, `PLUGINVAL-MACOS-CONSOLE.txt`, `BINARY-ARCHITECTURE.txt`, `SHA256SUMS.txt`.

## Combined evidence
`PREFLIGHT.txt`, `NI-DELIVERY-MANIFEST.txt`, `NI-DELIVERY-CHECKLIST.txt`, `CUSTOMER-INSTALLERS-SHA256.txt`, and the packaged QA-evidence archive.

Copy these from the successful frozen CircleCI artifacts. Do not manually recreate hashes/results.
