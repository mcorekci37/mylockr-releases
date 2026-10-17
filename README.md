# mylockr releases

Signed and notarized builds of the **mylockr** desktop app, a zero-knowledge password manager (formerly named mypass).

- **macOS** (Apple Silicon, macOS 11+; AutoFill needs macOS 14+): download the `.dmg` from the [latest release](https://github.com/mcorekci37/mylockr-releases/releases/latest), open it and drag mylockr to Applications.
- Verify the download: `shasum -a 256 mylockr_*.dmg` (`mypass_*.dmg` for 0.1.0) and compare with `SHA256SUMS` in the release.
- The app updates itself from this repository (signed update packages, `latest.json`). Apps installed as mypass 0.1.0 keep updating through GitHub's redirect from the old repository name.

This repository contains release files only; it has no source code.

- Website: https://mypass--4484.web.app
- Privacy: https://mypass--4484.web.app/privacy
- Support: https://mypass--4484.web.app/support
