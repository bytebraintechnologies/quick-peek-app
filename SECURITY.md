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

Official standalone releases contain a versioned executable and a matching `.sha256` file. Windows
must report a valid Authenticode signature from Bytebrain before the executable is run. A checksum
alone does not establish who published a file.

Unsigned historical builds are unsupported and should not be installed.
