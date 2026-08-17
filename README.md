# TME Copilot Releases

Public distribution repository for TME Copilot Windows installers.

This repository contains **only compiled release installers and public release information**.

It does not contain:

- source code
- TME API Token
- TME API Secret
- internal configuration
- private company data

## Latest release

The latest Windows installer is published under GitHub **Releases**.

Users should download:

`TME Copilot Setup.exe`

The TME Copilot application checks this repository for the latest release and can download updates automatically.

## Release process

1. Build the new Windows installer from the private source repository.
2. Create a new GitHub Release in this repository.
3. Use a version tag such as `v4.4`.
4. Upload `TME Copilot Setup.exe` as the release asset.
5. Publish the release.

Do not upload source code or API credentials here.

## Repository visibility

This repository is intentionally public so installed TME Copilot clients can check and download the latest release without requiring a GitHub account or authentication.

## Current release

v4.4
