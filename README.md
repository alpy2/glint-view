# Glint View

Glint View is a native macOS app for culling RAW photos. It's made for getting through a big shoot quickly: open a folder, flip through it, mark the keepers, and move on.

## Download

Latest version: [GlintView.dmg](https://github.com/alpy2/glint-view/releases/latest/download/GlintView.dmg)

Open the .dmg and drag Glint View into your Applications folder. The app is notarized by Apple, so it opens without any security warnings.

Runs on macOS 14 (Sonoma) and later, on both Apple Silicon and Intel Macs. Older versions are on the [releases page](https://github.com/alpy2/glint-view/releases).

## What it does

Glint View reads the JPEG preview embedded in each RAW instead of decoding the full image, so a card with a couple thousand photos opens in a few seconds rather than minutes.

Culling happens on the keyboard. Star ratings, color labels, picks and rejects all sit on the home row. Ratings and labels get written to XMP sidecar files, the same format Lightroom, Capture One, and Bridge read. If a sidecar already exists, Glint View merges into it rather than overwriting it, so any develop settings you already made stay put.

A few other things it does:

- Grid and full-screen Loupe views with a filmstrip
- Pixel-level magnifier, focus peaking, clipping warnings, live RGB histogram
- Groups bursts so you can keep the best frame and reject the rest in one go
- Imports straight off an SD card into dated folders
- Exports JPEGs
- Reads Sony ARW, Canon CR2/CR3, Nikon NEF, Fuji RAF, DNG, and others

No subscription, no analytics, works offline.

## About this repo

This repository hosts the release builds only. The source is not public.
