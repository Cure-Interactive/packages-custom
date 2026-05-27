# Packages Custom

Small helper package currently containing shared repository-manifest utilities.

## Version

Current version: `0.1.0`

## Files

- `cure_repo_manifest.py`: helpers for loading, normalizing, updating, and saving repository manifest data

This repository is mostly support code for `git_repository_update`. That standalone app vendors this helper directly, so it does not require this repository at runtime.

When vendoring this helper into another repository, record both the package version and the source commit from this repository.
