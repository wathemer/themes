# WaThemer themes

The theme store for [WaThemer](https://github.com/ayane-04/WaThemer). You browse and download these themes from
inside the app; this repository is what the app reads.

## Two kinds of theme

- **Colours**: themes built on WaThemer's colours, with or without a wallpaper.
- **Liquid Glass**: themes that use Liquid Glass, which always come with their wallpaper.

## Sending your theme

In WaThemer, open Themes, tap your theme, and share it (or choose "Send to the theme store" in versions that have it).
Send the file to the [@wathemer_chat](https://t.me/wathemer_chat) Telegram group. Every theme is reviewed before it is
published, and what is published is a cleaned copy of what was sent.

A theme carries its wallpaper and its font. Only send what you made or are free to share: the fonts and wallpapers in
this store are shared at their senders' own will.

## Taking something down

If a theme here contains something of yours that you want removed, open an issue in this repository.

## What is in here

- `store-index.txt`: the catalogue the app reads, signed by the maintainer. The app refuses it if the signature does not
  match one of the keys in `keys/`.
- `themes/`: thumbnails, screenshots and previews.
- `keys/`: the public keys the catalogue is checked against.
- The theme files themselves are in [Releases](https://github.com/wathemer/themes/releases).

This repository is never renamed or moved: every released version of WaThemer looks for it at this address.
