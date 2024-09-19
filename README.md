# StreamController Wallpaper Pack template repo
Some wallpapers for [StreamController](https://github.com/Core447/StreamController).

## Requirements / notes
Thumbnail (in store) must be 1000x360px 8bit RGB with Alpha channel (not indexed). Minimized files from tinypng do not work.

Attributions are not fully implemented. Just the general section is paresed and displayed in StreamController.

`manifest.json` contains extra/old fields. Check official spec for what should/must be present.

StreamController supports subfolders for images but they are not indicated in the interface.

## Recommended image sizes
Stream Deck models use distinct LCD displays behind each button. [Reported resolution](https://www.reddit.com/r/elgato/comments/p24mr1/comment/h8jmzw6/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) is as follows:

 * Stream Deck Mini - 72x72 pixels
 * Stream Deck - 72x72 pixels
 * Stream Deck XL - 96x96 pixels

Recomendation is to make images at least with double resolution. Therefore recomended resolutions for wallpapers are as follows:

 * Stream Deck Mini - 432x288 pixels
 * Stream Deck - 720x512 pixels
 * Stream Deck XL - 1104x768 pixels
