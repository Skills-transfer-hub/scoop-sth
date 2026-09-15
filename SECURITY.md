# Security policy

This repository distributes the Scoop manifest for STH.

## Report a vulnerability privately

Use [GitHub private vulnerability reporting](https://github.com/Skills-transfer-hub/scoop-sth/security/advisories/new). Do not disclose vulnerabilities, tokens, private keys or exploit details in public issues or pull requests.

Include the affected version, operating system, impact and minimal reproduction steps with sensitive data removed. Reports concerning STH binaries or suspected release tampering are in scope. Coordinate public disclosure with the maintainers after a fix or mitigation is available.

## Updates and integrity

Use the latest published stable release. Older versions do not have a guaranteed security backport policy. Download artifacts only from the official [STH releases](https://github.com/Skills-transfer-hub/sth-releases/releases) and verify SHA-256 checksums. Checksums detect changed downloads; they do not protect against a compromised publisher that can replace both an artifact and its checksum.

## Maintainer safeguards

Keep secret scanning and push protection enabled. Review changes to download URLs, hashes, installation scripts and automation. Use narrowly scoped publishing credentials and rotate any exposed credential. Never run code from an untrusted contribution with publishing credentials. Security alerts require investigation; enabling scanners alone does not certify a release as secure.
