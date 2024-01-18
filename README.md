# Art Book Next for ARKOS

(Original Theme: https://github.com/anthonycaccese/art-book-next-es)

This is the port of Art Book Next theme for JelOS. Only the POWKIDDY RGB30 (screen aspect ratio 1x1) is supported for now as I don't have other devices.

You can follow the changes in `aspect-ratio-1-1.xml` if you would like to port this for other devices. Welcome any PR.

## Instructions

To install this:
- Go to https://github.com/nkahoang/es-theme-art-book-next-arkos, click on Code -> Download ZIP
- Extract that zip out, there is a folder named `es-theme-art-book-next-arkos`.
- Either via sdcard copy or using ArkOS remote file, copy `es-theme-art-book-next-arkos` to `/roms/themes/`
- Enable the theme via EmulationStation settings (Start button) > UI Settings > `es-theme-art-book-next-arkos`
- Select aspect ratio (1:1), because the other aspect ratio isn't supported yet.

## Note for developer

- I recommend enabling SSH then making the change locally and just do `scp` push to the device, then restart EmulationStation in one go:
```
scp ./*.xml root@[IPADDRESS/HOSTNAME_OF_DEVICE]:/roms/themes/es-theme-art-book-next/; ssh root@[IPADDRESS/HOSTNAME_OF_DEVICE] -f "systemctl restart emulationstation"
```

### **Acknowledgments**
* Most system logos were sourced and modified from the excellent work done by Dan Patrick [here](https://archive.org/details/console-logos-professionally-redrawn-plus-official-versions).  I modified each to be compatible with EmulationStation's current SVG support.
* ChangaOne font is by [Eduardo Tunni](https://www.fontsquirrel.com/fonts/changa)
* Oxygen font is by [Vernon Adams](https://www.fontsquirrel.com/fonts/oxygen)
* Auto-Collection Genre background art created by [@nautipuss](https://github.com/nautipuss)

## **License**
(Attribution back to the OG repo by `anthonycaccese`: https://github.com/anthonycaccese/art-book-next-es)
Creative Commons CC-BY-NC-SA - https://creativecommons.org/licenses/by-nc-sa/2.0/
You are free to share and adapt this theme as long as you provide attribution back to me (and the above credits) as well share any updates you make under the same licence terms.
