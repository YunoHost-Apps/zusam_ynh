<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Zusam per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/zusam.svg)](https://dash.yunohost.org/appci/app/zusam) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/zusam.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/zusam.maintain.svg)

[![Installa Zusam con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zusam)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Zusam su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Zusam (/tsuˈzam/) is a free and open-source way to self-host private forums for groups of friends. Composed of a server written in PHP exposing a REST API and a lightweight webapp, Zusam is extensible and easy to install.
The goal is to make a stable, extensible, lightweight and user-friendly way to self-host private social groups.

### Features

- Links preview and embedded Youtube, Vimeo, Imgur, Soundcloud, Twitch, Bandcamp...
- Video and image upload
- Photo albums
- Public link generation for messages
- Completely responsive and mobile friendly
- Low server footprint


**Versione pubblicata:** 0.5.5~ynh1

**Prova:** <https://demo.zusam.org>

## Screenshot

![Screenshot di Zusam](./doc/screenshots/screenshot.jpg)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://zusam.org>
- Documentazione ufficiale per gli amministratori: <https://github.com/zusam/zusam/tree/master/documentation>
- Repository upstream del codice dell’app: <https://github.com/zusam/zusam>
- Store di YunoHost: <https://apps.yunohost.org/app/zusam>
- Segnala un problema: <https://github.com/YunoHost-Apps/zusam_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/zusam_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zusam_ynh/tree/testing --debug
o
sudo yunohost app upgrade zusam -u https://github.com/YunoHost-Apps/zusam_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
