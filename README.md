<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Lufi for YunoHost

[![Integration level](https://dash.yunohost.org/integration/lufi.svg)](https://ci-apps.yunohost.org/ci/apps/lufi/) ![Working status](https://ci-apps.yunohost.org/ci/badges/lufi.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/lufi.maintain.svg)

[![Install Lufi with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=lufi)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Lufi quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Lufi stores files and allows you to download them. Is that all? No. All the files are encrypted **by the browser**! It means that your files **never** leave your computer unencrypted.
The administrator of the Lufi instance you use will not be able to see what is in your file, neither will your network administrator, or your ISP.
The encryption key part of the URL is a anchor (Cf. [Fragment Identifier](https://en.wikipedia.org/wiki/Fragment_identifier)), that means this part is only processed client-side and does not reach the server. :-)


**Shipped version:** 0.07.0~ynh1

**Demo:** <https://demo.lufi.io/>

## Screenshots

![Screenshot of Lufi](./doc/screenshots/screenshot_lufi_1.png)

## Documentation and resources

- Official app website: <https://git.framasoft.org/luc/lufi>
- Official admin documentation: <https://framagit.org/luc/lufi/wikis/home>
- Upstream app code repository: <https://framagit.org/fiat-tux/hat-softwares/lufi>
- YunoHost Store: <https://apps.yunohost.org/app/lufi>
- Report a bug: <https://github.com/YunoHost-Apps/lufi_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/lufi_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/lufi_ynh/tree/testing --debug
or
sudo yunohost app upgrade lufi -u https://github.com/YunoHost-Apps/lufi_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
