# C2P LicenseRequester v1.4.0 one-click preview

## Package

- File: `C2P.LicenseRequester-v1.4.0-win-x64-OneClick.exe`
- Size: 74,077,308 bytes
- SHA-256: `8ED02A9D211F00CF9C7FEEBC58511C2FCEE7EBC320D69F3B3858E515D26A6503`
- Source: `LCA-C2PDev/C2P.LicenseRequester` tag `v1.4.0`, commit `4c6e3f2`
- Platform: Windows x64; self-contained .NET 8 WPF application

Download the setup EXE and open it on the intended Call2Prayer PROPlus PC. It installs for the current user, includes the required `yapi.dll` for optional YOCTO relay features, creates a Start menu entry, and opens License Requester. It does not issue or activate a license.

## Fingerprint V2

The requester derives a stable machine identity from MachineGuid and strong hardware anchors. Network adapter MAC addresses remain request metadata and do not affect the V2 fingerprint. The exported `C2P.MachineRequest/v2` is intended for the matching SAK Fingerprint V2 branch and PROPlus 2026.10.4.1 preview. Legacy v1 request import remains supported.

## Verification

All 14 License Requester automated tests passed. The self-contained publish produced the application EXE and `yapi.dll`. A sandbox install placed both files with hashes matching the publish output; the sandbox uninstall completed and removed the app. The SHA-256 above identifies the release asset.

Target-PC request-to-license interoperability, network adapter change behavior, and physical YOCTO relay operation remain operator preview checks. The setup EXE is unsigned, so Windows SmartScreen may ask for confirmation. Do not include customer request files or raw hardware evidence in public reports.

The prior 1.3.0 portable package and [release notes](RELEASE-NOTES-v1.3.0.md) remain available.
