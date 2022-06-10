# UW<sup>x</sup> - Ultrawide Experience <img align="right" src="images/icon128.png">

UW<sup>x</sup> is a chrome browser extensions enabling video zoom to better fit ultrawide aspect ratios.

## Hotkeys
| Hotkey | Video Aspect Ratio |
|  :---: |      :----:        |
|  Alt+1 |       16:9         | 
|  Alt+2 |       21:9         |
|  Alt+3 |       32:9         | 

## Example
Hardcoded black bars on top and bottom of 16:9 video (forcing a 21:9 aspect ratio for "cinematic" effect) will also show black bars on left and right on ultrawide monitors instead of filling the whole screen. With UW<sup>x</sup> using hotkey `Alt+2` on a 21:9 aspect ratio monitor will zoom in to fill the whole screen.
| 16:9 monitor                 | 21:9 ultrawide monitor       | 21:9 ultrawide monitor with UW<sup>x</sup> |
|------------------------------|------------------------------|--------------------------------------------|
| ![16_9.png](images/16_9.png) | ![21_9.png](images/21_9.png) | ![21_9_zoom.png](images/21_9_zoom.png)     |

## How to Install
Clone this git repository and navigate to the `chrome://extensions/` tab. Enable `Developer mode` in the top right corner and click `Load unpacked` in the top left. Navigate to this repository's root folder and click `Select Folder`. Done.

The extension can easily be remove by clicking `Remove` on the `chrome://extensions/` tab.

## Supported Platforms
| Prime Video | Netflix | Dinsey+ | Youtube |
|-|-|-|-|
| ![primevideo](images/Prime_Video-Logo.wine.png)  | ![netflix](images/Netflix-Logo.wine.png) | ![disney+](images/Disney%2B-Logo.wine.png) | ![youtube](images/YouTube-Logo.wine.png) |