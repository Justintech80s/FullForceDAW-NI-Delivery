# Native Instruments VST3 Delivery

## Release identity
- Product: Full Force DAW
- Version: 2.1.0
- Frozen validated commit: `087b974acc2ea741301691dfc4658149a8b0438c`
- CI authority: CircleCI
- Windows: x64
- macOS: Universal `arm64 + x86_64`

## Authoritative CircleCI artifact page

https://app.circleci.com/pipelines/github/Justintech80s/Just-Soundz/414/workflows/full-force-daw-vst3/jobs/501/artifacts

This page belongs to the successful **release-preflight (501)** job and contains the CI-produced Native Instruments delivery artifacts for the frozen candidate. It is the source for the exact customer installers and accompanying QA/integrity evidence; do not substitute rebuilt binaries.

## Verified customer installers

The exact customer installer files from the frozen delivery have now been independently received and SHA-256 verified:

| Platform | Exact file | Size | SHA-256 | Authoritative download source |
| --- | --- | ---: | --- | --- |
| Windows x64 | `FullForceDAW-2.1-Windows-x64-Setup.exe` | 2,440,203 bytes | `1bcb5f691d921b1d74fad057cc1e56ea13ebc6fe79efc66c899331536fe5b2d4` | [CircleCI release-preflight #501 artifacts](https://app.circleci.com/pipelines/github/Justintech80s/Just-Soundz/414/workflows/full-force-daw-vst3/jobs/501/artifacts) |
| macOS Universal | `FullForceDAW-2.1.0-macOS-unsigned.pkg` | 660,087 bytes | `2669ba50e6d5ce41e35f9a556287d13a4f11830005231b8aa792411b1ce08220` | [CircleCI release-preflight #501 artifacts](https://app.circleci.com/pipelines/github/Justintech80s/Just-Soundz/414/workflows/full-force-daw-vst3/jobs/501/artifacts) |

The macOS package remains explicitly **unsigned/not notarized**. These hashes identify the exact files; do not replace them with rebuilt binaries.

## Customer installers
**Windows:** `FullForceDAW-2.1-Windows-x64-Setup.exe`  
VST3 destination: `C:\Program Files\Common Files\VST3`

**macOS:** `FullForceDAW-2.1.0-macOS-unsigned.pkg`  
VST3 destination: `/Library/Audio/Plug-Ins/VST3`  
Status: **unsigned / not notarized**.

## Download links
- Windows installer: [CircleCI release-preflight #501 artifacts](https://app.circleci.com/pipelines/github/Justintech80s/Just-Soundz/414/workflows/full-force-daw-vst3/jobs/501/artifacts) — select `FullForceDAW-2.1-Windows-x64-Setup.exe`
- macOS installer: [CircleCI release-preflight #501 artifacts](https://app.circleci.com/pipelines/github/Justintech80s/Just-Soundz/414/workflows/full-force-daw-vst3/jobs/501/artifacts) — select `FullForceDAW-2.1.0-macOS-unsigned.pkg`
- SHA-256 manifest: **PENDING FROZEN ARTIFACT UPLOAD**

Do not substitute newly rebuilt binaries.

## QA license / activation
- QA license/activation mechanism: **PENDING NI/PRODUCT ACTIVATION DETAILS**
- Number/type of QA licenses: **PENDING NI CONFIRMATION**
- Serials/tokens/credentials: **DO NOT STORE IN THIS REPOSITORY**

Use an NI-approved secure channel for secrets and activation credentials.
