# Technobake oven downloads

Official compiled software downloads for Technobake Roast Runner ovens.
The oven source code is maintained separately in a private repository.

## Latest service update (restricted download)

**[v2026.10.13 — Restore oven reporting connectivity](https://github.com/andy-dextrous/technobake-downloads/releases/tag/v2026.10.13)**

Repairs missing reporting setup through the normal USB software update. Its
installer contains a legacy reporting credential, so downloads require authorised
access to the [private service release](https://github.com/andy-dextrous/technobake-roast-runner-oven-legacy/releases/tag/v2026.10.13).
There is no public installer for this service update. Contact your Technobake
service representative if you need it. Installation remains the usual USB process.

## Latest public installer

**[v2026.10.06 — Separator cleaning confirmation correction](https://github.com/andy-dextrous/technobake-downloads/releases/tag/v2026.10.06)**

- **[Download the latest oven update ZIP](https://github.com/andy-dextrous/technobake-downloads/releases/latest/download/cro-update.zip)**
- [Download this exact version](https://github.com/andy-dextrous/technobake-downloads/releases/download/v2026.10.06/cro-update.zip)
- [SHA256 checksums](https://github.com/andy-dextrous/technobake-downloads/releases/download/v2026.10.06/SHA256SUMS)

These downloads are public and require no GitHub login. Detailed changes and
verification limits are in the release notes.

## Using the download

Download **cro-update.zip**, not GitHub's automatic Source code archive.
Extract it onto the update USB, retaining `cro/cro-update.tgz`, and follow the
established supervised update procedure for your oven. Retain a known-good
rollback package. This update does not replace recipes or settings.

This repository distributes the compiled installer, checksums and release notes
only; it does not contain oven source code, service credentials or internal logs.
