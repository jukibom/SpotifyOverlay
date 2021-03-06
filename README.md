NOTE: This is a defunct project. Spotify changed their desktop client and this software no longer works as a result.

# SpotifyOverlay
A third-party Spotify client built specifically for OpenVR.

[![Spotify Overlay](https://i.imgur.com/xxSJjpn.png)](https://www.youtube.com/watch?v=4vb6xc_aLWk)

## Installation
Download all the files in /bin and put them somewhere on your computer, then run SpotifyOverlay.exe. Alternatively, you can download everything as a .zip archive [here](https://github.com/rrkpp/SpotifyOverlay/blob/master/release/SpotifyOverlay_v1_0.zip?raw=true) and extract it somewhere.

The first time you run the overlay, it will generate a .vrmanifest and tell SteamVR to auto-run Spotify Overlay whenever SteamVR is started. If you don't want the overlay to auto-run, you can disable it in SteamVR > Settings > Applications.

## How to Use
From any SteamVR application, just open the SteamVR Dashboard and look toward the bottom for your dashboard overlay buttons. You should see a "Spotify" overlay right next to "Steam" and "Desktop" (and any other overlays you have installed). The overlay will try connecting to Spotify when it first starts up, and if that fails (meaning Spotify wasn't running when SteamVR/the overlay launched), it'll retry every time you open the overlay. So if the overlay isn't doing anything and it doesn't seem to be connected to Spotify, just close the dashboard and re-open it, and it should load right up.

Click the green "Search" button in the top-right to open the keyboard and search for something, click the search results to play the track, and use the arrows to the right of the search results to scroll up/down. When you play a track from the search results, it'll drop you into the album that track is from. In other words, if you play a song from the search results and hit the skip button to move to the next track, it'll play the next track on that album.

## Credits / Thanks
* Carl Bystrom for documenting the local Spotify HTTP server, which made this overlay possible
* LibreVR for developing the open-source, MIT-licensed Revive project, which helped demonstrate how create a usable dashboard overlay, and from which the code for manifest generation was copied. Give him some support: https://github.com/LibreVR/Revive
