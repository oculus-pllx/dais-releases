# Parallax Dais releases

Signed release builds of the Parallax Dais, the control panel for Parallax EQEmu servers. This repository holds binaries and release notes only.

Each release has the Linux build, `index.json` (every release so far) and `index.json.sig`, an ed25519 signature. A Dais checks for updates here, downloads without a token, and refuses anything the signature doesn't cover. The public key is built into the Dais.

Releases are published only after review and a test on a Parallax test server. Don't install these by hand on a server that runs stock Spire.

Built on EQEmu Spire (Akkadius), maintained by Valorith, with Ultimate Spire (eniner) and straps' work.
