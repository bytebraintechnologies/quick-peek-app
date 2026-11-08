# Quick Peek for Windows

Quick Peek is a fast Windows file previewer. Select a file or folder in File Explorer and press
Space to inspect it without opening another application.

## Downloads

### Recommended: Microsoft Store

Use the Microsoft Store for the trusted production installation. Microsoft signs the package and
delivers updates automatically.

- [Install Quick Peek from Microsoft Store](https://apps.microsoft.com/detail/9PNXLCSBV6TT)
- Store ID: `9PNXLCSBV6TT`

### Portable preview

The [Releases](https://github.com/bytebraintechnologies/quick-peek-app/releases) page provides an
optional standalone preview. It is free to download but **not digitally signed**, so Windows may show
an Unknown publisher or “Windows protected your PC” warning, and Smart App Control may block it.

Use the portable preview only if you understand that limitation. Every preview has an explicit
`-unsigned.exe` filename, a matching SHA-256 checksum, and an immutable GitHub release.

## Highlights

- Preview source code, text, Markdown, JSON, XML, CSV, and spreadsheets.
- Read PDF, Word, PowerPoint, e-book, and email formats.
- Browse images, media, archives, folders, and 3D models.
- Search, compare, inspect metadata, print, and export without leaving the preview.
- Use either the Microsoft Store-managed production installation or a self-updating portable preview.

See the complete [Quick Peek feature catalog](FEATURES.md) for supported formats, navigation,
document tools, image and media capabilities, folder browsing, export, and privacy behavior.

## Installation

For production, [install Quick Peek through Microsoft Store](https://apps.microsoft.com/detail/9PNXLCSBV6TT).

For the portable preview:

1. Open the latest GitHub release.
2. Download `QuickPeek-<version>-win-x64-unsigned.exe` and its `.sha256` file.
3. Verify that the downloaded executable's SHA-256 value matches the checksum.
4. Run it only if you accept the Windows unsigned-application warning.

The repository intentionally contains no application source code. It is the official distribution,
release-notes, and support repository for the proprietary Quick Peek application.

## Support and security

- Read [SUPPORT.md](SUPPORT.md) before opening a support request.
- Report vulnerabilities privately as described in [SECURITY.md](SECURITY.md).
- See [PRIVACY.md](PRIVACY.md) for the application's data-handling summary.

Copyright © 2026 Bytebrain Technology Solutions. All rights reserved.
