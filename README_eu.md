<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Zusam YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/zusam)](https://ci-apps.yunohost.org/ci/apps/zusam/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/zusam)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/zusam)

[![Instalatu Zusam YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zusam)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Zusam YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Zusam (/tsuˈzam/) is a free and open-source way to self-host private forums for groups of friends. Composed of a server written in PHP exposing a REST API and a lightweight webapp, Zusam is extensible and easy to install.
The goal is to make a stable, extensible, lightweight and user-friendly way to self-host private social groups.

### Features

- Links preview and embedded Youtube, Vimeo, Imgur, Soundcloud, Twitch, Bandcamp...
- Video and image upload
- Photo albums
- Public link generation for messages
- Completely responsive and mobile friendly
- Low server footprint


**Paketatutako bertsioa:** 0.5.6~ynh1

**Demoa:** <https://demo.zusam.org>

## Pantaila-argazkiak

![Zusam(r)en pantaila-argazkia](./doc/screenshots/screenshot.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://zusam.org>
- Administratzaileen dokumentazio ofiziala: <https://github.com/zusam/zusam/tree/master/documentation>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/zusam/zusam>
- YunoHost Denda: <https://apps.yunohost.org/app/zusam>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/zusam_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/zusam_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zusam_ynh/tree/testing --debug
edo
sudo yunohost app upgrade zusam -u https://github.com/YunoHost-Apps/zusam_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
