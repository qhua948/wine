<p align="center">
    <img src="https://github.com/mmtrt/WINE_AppImage/raw/master/wine.svg" alt="WINE logo" width=128 height=128>

<h2 align="center">WINE AppImage</h2>

  <p align="center">WINE AppImage (unofficial) AppImages by GitHub Actions Continuous Integration
    <br>
    <a href="https://github.com/mmtrt/WINE_AppImage/issues/new">Report bug</a>
    ·
    <a href="https://github.com/mmtrt/WINE_AppImage/issues/new">Request feature</a>
    ·
    <a href="https://github.com/mmtrt/WINE_AppImage/releases">Download AppImage</a>
  </p>
</p>

## Info
 * This AppImage does not have any GPU drivers see requirements below before getting angry at me.

## Get Started

Download the latest release from

| Stable | Devel | Staging |
| ------- | --------- | --------- |
| <img src="https://github.com/mmtrt/WINE_AppImage/raw/master/wine.svg" height=100> | <img src="https://github.com/mmtrt/WINE_AppImage/raw/master/wine.svg" height=100> | <img src="https://github.com/mmtrt/WINE_AppImage/raw/master/wine.svg" height=100> |
| [Download](https://github.com/mmtrt/WINE_AppImage/releases/tag/continuous-stable) | [Download](https://github.com/mmtrt/WINE_AppImage/releases/tag/continuous-devel) | [Download](https://github.com/mmtrt/WINE_AppImage/releases/tag/continuous-staging) |


### Executing
#### File Manager
Just double click the `*.AppImage` file and you are done!

> In normal cases, the above method should work, but in some rare cases
the `+x` permissisions. So, right click > Properties > Allow Execution
#### Terminal
```bash
./wine-*.AppImage
```
```bash
chmod +x wine-*.AppImage
./wine-*.AppImage
```

In case, if FUSE support libraries are not installed on the host system, it is
still possible to run the AppImage

```bash
./wine-*.AppImage --appimage-extract
cd squashfs-root
./AppRun
```

## Requirements
 * Install required GPU driver pkgs for you GPU both `amd64` & `i386`.
```
MESA
NVIDIA
INTEL
AMD
```
