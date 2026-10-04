# C2P LicenseRequester v1.3.0

## Portable Windows x64 package

- File: `C2P.LicenseRequester-v1.3.0-win-x64-portable.zip`
- Contents: `C2P.LicenseRequester.exe` and required `yapi.dll`
- Package SHA-256: `0B99B53ED4767A234D83E4D1755335E5CD7B79CF9F6161844123A211BE13CA6A`
- Deployment: extract both files into the same writable folder and run the executable; no installer or separate .NET Desktop Runtime is required.

## What's new

- Optional YOCTO USB relay step with relay identity capture in the machine request.
- Editable logical name, including confirmed write and persistent save to the connected YOCTO module.
- Supervised relay diagnostics: live output/beacon state, confirmed two-second pulse test, beacon toggle, and Force OFF.
- Safe relay/beacon reset when leaving the relay step or closing the requester.

## Notes for prospects

Run the requester on the PC where Call2Prayer PROPlus will be used. The generated request includes machine-binding data and may include customer, site, and optional relay identity data. Review the exported JSON/TXT/ZIP request package before sharing it with approved Call2Prayer support or licensing staff.

The YOCTO relay is optional. If used, keep external loads safe before running relay diagnostics. `yapi.dll` must remain beside `C2P.LicenseRequester.exe` after extraction.
