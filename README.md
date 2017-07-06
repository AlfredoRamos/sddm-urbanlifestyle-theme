### About

A simple and colorful SDDM theme

[![Latest stable version](https://img.shields.io/github/tag/AlfredoRamos/urbanlifestyle-sddm-theme.svg?style=flat-square&maxAge=3600&label=stable)](https://github.com/AlfredoRamos/urbanlifestyle-sddm-theme/releases/latest) [![License](https://img.shields.io/github/license/AlfredoRamos/urbanlifestyle-sddm-theme.svg?style=flat-square)](https://raw.githubusercontent.com/AlfredoRamos/urbanlifestyle-sddm-theme/master/LICENSE)

Background image *Urban LifeStyle* by [snyp](http://r0pyns.deviantart.com/) (r0pyns) was taken from [anime-pictures.net](https://anime-pictures.net/pictures/view_post/100739)

### Dependencies
- Qt >= 5.6

### Preview
![Urban LifeStyle](https://raw.githubusercontent.com/AlfredoRamos/urbanlifestyle-sddm-theme/master/images/urbanlifestyle.jpg)

### Installation
**Arch Linux** (using [pacaur](https://wiki.archlinux.org/index.php/Pacaur))

```shell
pacaur -Sa urbanlifestyle-sddm-theme
```
___
**Other GNU/Linux distros**
- Download the [latest release](https://github.com/AlfredoRamos/urbanlifestyle-sddm-theme/releases/latest)
- Decompress the `*.zip` or `*.tar.gz` file
- Copy all files and directories into `/usr/share/sddm/themes/urbanlifestyle/`

### Usage
- Open up your `/etc/sddm.conf` file and set `urbanlifestyle` as your current theme

```shell
[Theme]
# Current theme name
Current=urbanlifestyle
```

### Configuration
You can change some theme settings to fit your preferences, these values are located in the [theme.conf](https://github.com/AlfredoRamos/urbanlifestyle-sddm-theme/blob/master/theme.conf) file.

The avatar image size should be at least 100x100 px. For more information, refer to the Arch wiki.
- [SDDM: Changing your avatar](https://wiki.archlinux.org/index.php/SDDM#Changing_your_avatar)

For the time and date format, please refer to the Qt QML docs.
- [Date QML Type](https://doc.qt.io/qt-5/qml-qtqml-date.html)
