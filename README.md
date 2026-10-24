# Zuben

Zuben is a native Windows browser built on Chromium through CEF. The repository also contains the Thai product website.

## Downloads

- [Windows x64 preview](https://github.com/teera3447/zuben-browser/releases/download/v0.1.0-preview.1/Zuben-Native-Windows-x64.zip)
- [Native browser source archive](https://github.com/teera3447/zuben-browser/releases/download/v0.1.0-preview.1/Zuben-Native-source.zip)

Extract the complete Windows ZIP and run `zuben.exe`. Keep the adjacent CEF files and `extensions/uBOLite` folder in place.

This is a preview build. It compiled successfully, but has not yet been smoke-tested interactively on Windows. It bundles uBOLite (Manifest V3); the supplied full uBlock Origin 1.75.0 package uses Manifest V2 and is not loaded by this Chromium build.

## Website

The root contains a static HTML, CSS and JavaScript site. Vercel deploys it directly from the repository without a build command.
