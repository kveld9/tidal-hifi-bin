# tidal-hifi-bin
Template file for Tidal Hi-Fi for Void Linux distribution.

## Installation steps.
1. Download this repo as a zip.
2. Extract the content.
3. Rename the folder ```tidal-hifi-bin-main``` to ```tidal-hifi-bin```.
4. Move the folder to ```void-packages/srcpkgs```.
5. Execute ```./xbps-src pkg -j$(nproc) tidal-hifi-bin```. # remember to stay in the void-packages directory.
6. Install the package by executing ```xi tidal-hifi-bin```. # remember to have installed "xtools" package for "xi" command.


## Credits.
- [tidal-hifi](https://github.com/Mastermindzh/tidal-hifi)
- [tidal-hifi-bin - AUR](https://aur.archlinux.org/packages/tidal-hifi-bin)
- [xbps-src](https://github.com/void-linux/void-packages)
