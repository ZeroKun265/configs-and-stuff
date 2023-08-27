# Monochrome Rice for KDE Wayland (2023) (Arch Linux)
A step by step guide to configure my kde+arch (or kde in general, but somethings might be arch-specific) with the appearence i want. An updated version of [this guide](https://github.com/westofer/monochrome-theme)

**To see how it will look like you can go to [this post on the r/unixporn subreddit](https://www.reddit.com/r/unixporn/comments/162lsoc/kde_monochrome_kde_i_kinda_followed_a_guide_first/)**

## 1. Enabling rounded corners
To enable rounded corners you can install [KDE Rounded Corners](https://github.com/matinlotfali/KDE-Rounded-Corners) and leave it basically as default:
1. Change active window border radius to 15
2. Change both shadows to 2
3. You might need to open the "Inclusions and Exclusions" tab to insert Konsole: Open the settings, open a new Konsole window, refresh, move to include

## 2. Global theme
From the settings >> Global Themes >> Get New Global themes >> Search for “monochrome” >> install and apply

## Konsole Scheme

1. From the konsole >> settings >> manage profiles >>
2. New Profile >> Appereance >> Get New >>
3. Search for "Monochrome" >> Install >> exit >>
4. Select Monochrome Konsole
5. Change opacity to 3'% (blur should be enabled by default but check(
6. Go to Miscellaneous and change margin to 15
7. Exit and set the new profile as default.
8. Restart konsole for changes to take effect)
9. Rightclick >> Set toolbars shown >> Disable them all
10. Remove titlebar and frame

## Installing icons
Installing this iconpack (manual installation with the tar.gz since the kde plugin browser doesn't fint it)

## Configure the panel
1. In Edit Modehrink the panel
2. Enable Center
3. Enable always visible

The widgets should be like this: 
```

Application Launcher | Panel Spacer | Icons-only Taskmanager | Panel spacer | Pager | System Tray | Peek at Desktop

```

1. Change Application Launcher Icon to `arch-icon-light-grey.png` available in the same folder as this guide
2. Add 4 Desktops in a 2x2 setup from the Pager
3. Change the System Tray icons to always show things like battery and disable other useless stuff

## Wallpaper
Apply the wallpapr `wallpaper_monochrome.jpg` available in the same folder as this guide`



