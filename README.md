# Deadlock Buy Overlay

Pop-up cards on your stream whenever an item is bought in Deadlock. Show only your own purchases, your team's, or everyone's.

![Purchase cards on a stream](screenshots/overlay.webp)

Pick a style, where the cards sit, how long they stay, and what they show:

![Deadlock, Glass and Minimal card styles](screenshots/styles.webp)

| Control page | First-run setup |
| --- | --- |
| ![Control page with settings and live preview](screenshots/control.webp) | ![Setup step for choosing what pops up](screenshots/setup.webp) |

## Install

1. Download the zip from the [latest release](https://github.com/negativeblueprint/deadlock-buy-overlay-releases/releases/latest).
2. Extract it anywhere, for example your Documents folder.
3. Double-click `Start.cmd`. If Windows says it protected your PC, click **More info**, then **Run anyway**.
4. A browser tab opens and walks you through setup, including adding the overlay to OBS.

If Node.js is not installed, `Start.cmd` installs it for you. New versions show an **Update now** button in the overlay's control page, so you only download once.

## Good to know

Cards come from the match's spectator broadcast, so they appear a few seconds to tens of seconds after the purchase. Valve does not broadcast every match; when it skips yours, the control page tells you.

This repo only holds the downloads.
