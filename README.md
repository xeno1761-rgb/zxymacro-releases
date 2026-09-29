# ZxyMacro releases

Release artefacts and the update feed for **ZxyMacro**.

This repository holds **only** build outputs: the installer, its `.blockmap` and
`latest.yml` — the manifest that installed copies of ZxyMacro read when they check
for updates. The source lives in a private repository.

## Installing

Download the newest `ZxyMacro-<version>-Setup.exe` from
[Releases](https://github.com/xeno1761-rgb/zxymacro-releases/releases/latest) and run it.

## Updating

Installed copies read `latest.yml` from the newest release on this repository.
Updates are never fetched automatically: the user presses **Check for updates** in
Settings. Windows may show a SmartScreen warning because the build is not
code-signed.
