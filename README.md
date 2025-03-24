<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Zusam for YunoHost

[![Integration level](https://apps.yunohost.org/badge/integration/zusam)](https://ci-apps.yunohost.org/ci/apps/zusam/)
![Working status](https://apps.yunohost.org/badge/state/zusam)
![Maintenance status](https://apps.yunohost.org/badge/maintained/zusam)

[![Install Zusam with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zusam)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Zusam quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Zusam (/tsuˈzam/) is a free and open-source way to self-host private forums for groups of friends. Composed of a server written in PHP exposing a REST API and a lightweight webapp, Zusam is extensible and easy to install.
The goal is to make a stable, extensible, lightweight and user-friendly way to self-host private social groups.

### Features

- Links preview and embedded Youtube, Vimeo, Imgur, Soundcloud, Twitch, Bandcamp...
- Video and image upload
- Photo albums
- Public link generation for messages
- Completely responsive and mobile friendly
- Low server footprint


**Shipped version:** 0.5.6~ynh2

**Demo:** <https://demo.zusam.org>

## Screenshots

![Screenshot of Zusam](./doc/screenshots/screenshot.jpg)

## Documentation and resources

- Official app website: <https://zusam.org>
- Official admin documentation: <https://github.com/zusam/zusam/tree/master/documentation>
- Upstream app code repository: <https://github.com/zusam/zusam>
- YunoHost Store: <https://apps.yunohost.org/app/zusam>
- Report a bug: <https://github.com/YunoHost-Apps/zusam_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/zusam_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zusam_ynh/tree/testing --debug
or
sudo yunohost app upgrade zusam -u https://github.com/YunoHost-Apps/zusam_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
