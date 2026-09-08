# Changelog

## [Unreleased]


## [0.1.1-demo]

- Fixes the update check. It asked GitHub for /releases/latest, which skips prereleases — the demo is one, so the answer was always "no release" and the check reported a failure. It now reads the release list and takes the newest published tag.
- The download button on thewire.m51v5.com was reading the same endpoint and had the same blind spot; it now finds the build instead of falling back to the releases page.
- No gameplay changes: same Chapter 1, floors 0–6 ("The Cellar"), same English and Arabic.
## [0.1.0-demo]

- First public build. Chapter 1, floors 0–6 ("The Cellar"): ls, cd, cat, file, find, grep, hidden files, awkward filenames, permissions, 2>/dev/null.
- English and Arabic. Windows 10/11, 64-bit, one executable, no installer.
- Update check at launch and from Settings (one request to GitHub, can be switched off).

