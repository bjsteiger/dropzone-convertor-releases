# Dropzone Convertor releases

This is the download and update home for Dropzone Convertor, a menu bar
app for macOS that converts Markdown to Word, PDF, HTML, and more with a
drag and a drop.

## Installing

Grab the DMG from the latest entry on the
[Releases page](https://github.com/bjsteiger/dropzone-convertor-releases/releases),
open it, and drag the app to Applications. Builds are Developer ID signed
and notarized, so the app opens normally with no Gatekeeper warning.

## Updates

Installed copies check `appcast.xml` in this repository and update
themselves through [Sparkle](https://sparkle-project.org). Every update
archive is signed, and the app verifies the signature before installing
anything, so this repository being public does not weaken that chain.

## License

Dropzone Convertor is MIT licensed (see [LICENSE](LICENSE)). Bundled
components keep their own licenses: conversion is powered by
[Pandoc](https://pandoc.org) (GPL, shipped as a separate unmodified binary,
source available from its project), and updates by
[Sparkle](https://github.com/sparkle-project/Sparkle) (MIT).
