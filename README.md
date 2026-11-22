# AURN pack

Files read by the AURN Launcher: `pack.json` (pack version + every file with its sha1), `news.json` (home-page news)
and `files/` (only AURN's own files: aurnfolk, AURN resource packs, configs). Third-party mods are not stored here;
the launcher downloads them from Modrinth or CurseForge.

Update: run `tools/build_pack.py --out <this folder>` in the launcher project, then commit and push.

## Play AURN

Download the launcher from the [latest release](https://github.com/Jmmusa/aurn-pack/releases/latest)
(Windows: `AURN-Launcher-…-windows.exe`), run it, sign in with Microsoft and press Play.

## Third-party licences
- `files/mods/swemaddendum-1.0.1--1.21.1.jar`: SWEM Addendum by EvangeliX, GPLv3, unmodified. Source: https://github.com/EvangeliX-2501/swem-addendum (project page: https://www.curseforge.com/minecraft/mc-mods/swem-addendum)
