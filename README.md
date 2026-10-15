# Quick Nucleus releases

This repository distributes checksummed Ubuntu 24.04 amd64/arm64 install bundles,
runtime image references, and matching Python SDK and developer CLI wheels.
The Quick source repository remains private. Releases are unsigned: HTTPS and
the publication account establish trust; checksums detect artifact corruption.

Install the recommended release with `curl -fsSL https://get.warpica.com | sudo bash`, or download a versioned release from this repository's Releases page. Release
metadata under `releases/` records source provenance and frozen artifact hashes.
Each release includes a pinned bootstrap script that verifies acquisition and starts the guided installation.
