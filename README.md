# Full Force DAW — Native Instruments Delivery

**Private delivery repository — Native Instruments QA/release use only**

## Validated release candidate
- Product: **Full Force DAW**
- Version: **2.1.0**
- Frozen source release candidate: `087b974acc2ea741301691dfc4658149a8b0438c`
- Validation authority: **CircleCI**
- Policy: do not rebuild or modify this candidate for delivery. Any NI-requested correction becomes a new candidate.

The validated CircleCI chain passed web/native tests, Windows VST3 validation, Windows customer-installer QA, macOS VST3/package/host QA, and the combined release preflight.

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
