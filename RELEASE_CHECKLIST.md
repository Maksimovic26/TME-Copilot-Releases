# Release checklist

For every new TME Copilot version:

1. Build the installer in the private source repository.
2. Make sure the installer is named exactly:
   `TME Copilot Setup.exe`
3. Open this public repository.
4. Create a new GitHub Release.
5. Set the tag to the application version, for example:
   `v4.4`
6. Upload `TME Copilot Setup.exe`.
7. Add or update the release notes.
8. Publish the release.

Do NOT upload:

- source code
- `.env`
- API Token
- API Secret
- private configuration
- internal company documents

The application updater reads the latest public GitHub Release and downloads the installer asset.
