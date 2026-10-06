# Full Force DAW — Native Instruments Delivery

**Private delivery repository — Native Instruments QA/release use only**

## Validated release candidate
- Product: **Full Force DAW**
- Version: **2.1.0**
- Frozen source release candidate: `087b974acc2ea741301691dfc4658149a8b0438c`
- Validation authority: **CircleCI**
- Policy: do not rebuild or modify this candidate for delivery. Any NI-requested correction becomes a new candidate.

The validated CircleCI chain passed web/native tests, Windows VST3 validation, Windows customer-installer QA, macOS VST3/package/host QA, and the combined release preflight.

## Official CircleCI release artifacts

**Artifact page:** https://app.circleci.com/pipelines/github/Justintech80s/Just-Soundz/414/workflows/full-force-daw-vst3/jobs/501/artifacts

This is the successful CircleCI **release-preflight job 501** artifact page for the frozen release candidate. It holds the Native Instruments delivery outputs produced by CI, including the validated Windows customer installer, macOS customer package, NI delivery manifest/checklist, installer SHA-256 information, combined preflight evidence, and Windows/macOS QA evidence. Use this page as the authoritative CI download source for the frozen artifacts.

## Verified customer installers

The exact customer installer files from the frozen delivery have now been independently received and SHA-256 verified:

| Platform | Exact file | Size | SHA-256 | Authoritative download source |
| --- | --- | ---: | --- | --- |
| Windows x64 | `FullForceDAW-2.1-Windows-x64-Setup.exe` | 2,440,203 bytes | `1bcb5f691d921b1d74fad057cc1e56ea13ebc6fe79efc66c899331536fe5b2d4` | [CircleCI release-preflight #501 artifacts](https://app.circleci.com/pipelines/github/Justintech80s/Just-Soundz/414/workflows/full-force-daw-vst3/jobs/501/artifacts) |
| macOS Universal | `FullForceDAW-2.1.0-macOS-unsigned.pkg` | 660,087 bytes | `2669ba50e6d5ce41e35f9a556287d13a4f11830005231b8aa792411b1ce08220` | [CircleCI release-preflight #501 artifacts](https://app.circleci.com/pipelines/github/Justintech80s/Just-Soundz/414/workflows/full-force-daw-vst3/jobs/501/artifacts) |

The macOS package remains explicitly **unsigned/not notarized**. These hashes identify the exact files; do not replace them with rebuilt binaries.

## Customer delivery
| Platform | Customer artifact | Status |
| --- | --- | --- |
| Windows x64 | `FullForceDAW-2.1-Windows-x64-Setup.exe` | Validated; upload exact frozen CircleCI artifact |
| macOS Universal | `FullForceDAW-2.1.0-macOS-unsigned.pkg` | Validated; upload exact frozen CircleCI artifact |

The macOS package is **unsigned/not notarized by release-plan decision**.

See [VST3-DELIVERY.md](VST3-DELIVERY.md), [QA-EVIDENCE.md](QA-EVIDENCE.md), and [NI-DELIVERY-RESPONSE.md](NI-DELIVERY-RESPONSE.md).

## Kontakt Player / Leap
This is a **separate submission track**. See [KONTAKT-LEAP-SUBMISSION.md](KONTAKT-LEAP-SUBMISSION.md).

## Access
This repository is private. NI personnel need repository access before private GitHub links can be used. Installer binaries must be copied from the frozen CircleCI artifacts; they are not to be reconstructed here.
