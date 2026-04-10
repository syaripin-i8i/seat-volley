# seat-volley

Packagist source repository for the SeAT plugin portion of Volley.

## Purpose

- This repository contains only the Laravel / SeAT plugin files.
- The full development repository lives in `C:\Codex\volley`.
- The plugin source of truth inside that repo is `C:\Codex\volley\seat-plugin`.

## Important

- Packagist updates are driven from this repository, not from `C:\Codex\volley`.
- Changes made under `C:\Codex\volley\seat-plugin` must be mirrored here before tagging a release.
- Do not copy `engine/` code into this repository.

## Release Flow

1. Implement and verify changes in `C:\Codex\volley`.
2. Mirror the relevant `seat-plugin/` files into this repository.
3. Bump `composer.json` version here.
4. Commit and tag here.
5. Push here and confirm Packagist picks up the new version.
