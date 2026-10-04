# C2P LicenseRequester downloads

## Download and run

**Latest one-click preview (1.4.0):** Download [C2P.LicenseRequester-v1.4.0-win-x64-OneClick.exe](https://github.com/LCA-C2PDev/C2P.PROPlus.Release.LicenseRequester/releases/download/v1.4.0/C2P.LicenseRequester-v1.4.0-win-x64-OneClick.exe) and open it on the Windows x64 PC that will run Call2Prayer PROPlus. The per-user setup installs the self-contained requester and its required `yapi.dll`, then opens the app. No separate .NET Desktop Runtime or administrator elevation is required.

Fingerprint V2 requests from 1.4.0 require the matching SAK Fingerprint V2 branch and PROPlus 2026.10.4.1 preview licensing workflow. This release is a preview while target-PC interoperability and physical YOCTO checks continue.

Verify the one-click EXE before use:

```text
SHA-256: 8ED02A9D211F00CF9C7FEEBC58511C2FCEE7EBC320D69F3B3858E515D26A6503
```

The [checksum file](C2P.LicenseRequester-v1.4.0-win-x64-OneClick.sha256.txt) and [release notes](RELEASE-NOTES.md) are also available here. The previous [1.3.0 portable ZIP](C2P.LicenseRequester-v1.3.0-win-x64-portable.zip) remains available for manual extraction; keep its `yapi.dll` beside its executable.

# Purpose, privacy, and consent

Thank you for your interest in the Call2Prayer Advance Automation Solution. This utility helps you prepare the information needed to request your Call2Prayer license and subscription.

## What this app collects

- customer details entered by **you**
- site details entered by **you**
- PC digital fingerprint captured automatically. Run this app on the PC where you intend to install Call2Prayer.

## What this app does not do

- it does not install services
- it does not run in the background
- it does not activate the product
- it does not issue a license
- it does not contact a licensing server by itself

## Privacy note

The generated request is intended for the Call2Prayer PROPlus licensing administrator so a license with the appropriate features and subscription period can be prepared for this machine.

The exported files may contain:

- personal contact details
- organization and site information
- hardware-derived machine identity values

Only share the generated files with the intended licensing contact or approved support channel.

## Consent

By continuing, you confirm that:

- you are authorized to prepare the request for this customer or site
- you understand that machine identity data will be exported into the request artifact
- you understand that the request artifact should be reviewed before sharing
- you give consent to Call2Prayer PROPlus licensing administrator to use the prepared request for further processing.
