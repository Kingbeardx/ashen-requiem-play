# Ashen Requiem — browser playtest

This repository contains only the compiled browser game and audio license/source
notices. Development source files and original modeling/animation assets are not
published here. Third-party assets retain their respective licenses; this is not
a blanket license to reuse game assets.

## Enable the play link (repository owner, once)

Open Settings → Pages → Build and deployment. Choose **Deploy from a branch**,
select **main**, choose **/(root)**, and Save. Wait for GitHub to display **Visit
site**, then text that link to testers.

Expected URL after successful deployment:
https://kingbeardx.github.io/ashen-requiem-play/

## iPhone

Open the deployed site in Safari, hold the phone sideways, and tap PLAY. The first
download is approximately 91 MiB before hosting compression. Use normal browsing
if you want saves retained. Saves stay in this browser/device and are separate
from the Android app. Clearing website data may remove them.

The existing game was exported using Godot 4.6.3, single-threaded WebGL 2 /
Compatibility rendering. Chromium browser smoke testing covered menu input,
New Game, Skip, movement, LIGHT input, audio activation, and IndexedDB storage.
iPhone Safari hardware testing and device performance are not yet verified.

Keep all supplied web files together. Opening index.html directly from a phone's
Files app is unsupported; use the HTTPS game link after hosting is enabled.
