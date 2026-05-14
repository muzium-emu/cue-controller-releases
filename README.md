# CUE Controller Releases

Public release feed and downloads for CUE Controller.

This repository hosts public update metadata and release assets only. The CUE Controller source code remains private.

## Appcast

```text
https://raw.githubusercontent.com/muzium-emu/cue-controller-releases/main/appcast.xml
```

## Release Flow

1. Build, sign, notarize, and staple CUE Controller.
2. Create the Sparkle update archive.
3. Generate `appcast.xml` with Sparkle's `generate_appcast` tool.
4. Upload the archive as a GitHub Release asset.
5. Commit the updated `appcast.xml` to this repository.
