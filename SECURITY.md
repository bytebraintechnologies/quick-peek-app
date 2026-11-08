# Security policy

## Reporting a vulnerability

Do not disclose a suspected vulnerability in a public issue.

Use GitHub's
[private vulnerability reporting](https://github.com/bytebraintechnologies/quick-peek-app/security/advisories/new)
to provide affected versions, reproduction steps, expected impact, and any supporting files. Remove
personal or confidential content from samples whenever possible.

Bytebrain will acknowledge a complete report, investigate it, and coordinate disclosure after a fix
is available. Please do not publish details while the investigation is active.

## Verifying downloads

The Microsoft Store package is the trusted production distribution and is signed by Microsoft.

GitHub portable previews are intentionally unsigned and carry `-unsigned.exe` in their names. Each
has a matching `.sha256` file and is published in an immutable release. The checksum detects a
modified download but does not establish a Windows publisher identity. Windows may warn about or
block these previews.

Unsigned historical builds are unsupported and should not be installed.
