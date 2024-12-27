<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Zusam voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/zusam)](https://ci-apps.yunohost.org/ci/apps/zusam/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/zusam)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/zusam)

[![Zusam met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zusam)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Zusam snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Zusam (/tsuˈzam/) is a free and open-source way to self-host private forums for groups of friends. Composed of a server written in PHP exposing a REST API and a lightweight webapp, Zusam is extensible and easy to install.
The goal is to make a stable, extensible, lightweight and user-friendly way to self-host private social groups.

### Features

- Links preview and embedded Youtube, Vimeo, Imgur, Soundcloud, Twitch, Bandcamp...
- Video and image upload
- Photo albums
- Public link generation for messages
- Completely responsive and mobile friendly
- Low server footprint


**Geleverde versie:** 0.5.6~ynh1

**Demo:** <https://demo.zusam.org>

## Schermafdrukken

![Schermafdrukken van Zusam](./doc/screenshots/screenshot.jpg)

## Documentatie en bronnen

- Officiele website van de app: <https://zusam.org>
- Officiele beheerdersdocumentatie: <https://github.com/zusam/zusam/tree/master/documentation>
- Upstream app codedepot: <https://github.com/zusam/zusam>
- YunoHost-store: <https://apps.yunohost.org/app/zusam>
- Meld een bug: <https://github.com/YunoHost-Apps/zusam_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/zusam_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zusam_ynh/tree/testing --debug
of
sudo yunohost app upgrade zusam -u https://github.com/YunoHost-Apps/zusam_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
