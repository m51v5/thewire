# Changelog

## [Unreleased]

## [0.2.0-demo]

- Every board now grades you. Clearing it opens a report card: hints, commands, time, and a medal. Bronze: cleared. Silver: no hints. Gold: no hints and you typed the command that found the key.
- The board picker shows the medal on each cleared board and your best run under it. Cleared boards allow typing on replay, so you can go back for gold on floors 0-2 too.

## [0.1.1-demo]

- Fixes the update check. It asked GitHub for /releases/latest, which skips prereleases — the demo is one, so the answer was always "no release" and the check reported a failure. It now reads the release list and takes the newest published tag.
- The download button on thewire.m51v5.com was reading the same endpoint and had the same blind spot; it now finds the build instead of falling back to the releases page.
- No gameplay changes: same Chapter 1, floors 0–6 ("The Cellar"), same English and Arabic.

## [0.1.0-demo]

- First public build. Chapter 1, floors 0–6 ("The Cellar"): ls, cd, cat, file, find, grep, hidden files, awkward filenames, permissions, 2>/dev/null.
- English and Arabic. Windows 10/11, 64-bit, one executable, no installer.
- Update check at launch and from Settings (one request to GitHub, can be switched off).

