# ROCKY QUOTE STUDIO — Official Updates

This repository is the public update-notification destination for ROCKY QUOTE STUDIO, a Photoshop UXP plugin for wedding album typography.

## Current status
- Office beta: **v0.5.3 — TEST 06** (private testing; not a public production release).
- **No public downloadable release has been published yet.**
- The plugin checks GitHub Releases for a newer published version. It continues working offline.
- Updates are **notifications**, not silent installation. A user must review and install a supported plugin update.
- Quote-pack auto-sync is a future feature and is **not** active in this beta.

## Publishing the first test update
1. Finish the office beta and confirm that Photoshop UXP is stable.
2. Prepare a distributable build without exposing proprietary source files.
3. On GitHub, open **Releases → Draft a new release**.
4. Create a tag higher than the installed version, for example `v0.5.4`.
5. Attach the approved installer/package and describe exactly what changed.
6. Publish the release. The plugin's **Check Online** feature can then detect it.

## Security and licensing
Do not commit private API keys, customer data, proprietary font files, or paid plugin source code to this public repository.

Support and distribution information will be added when the commercial release is ready.
