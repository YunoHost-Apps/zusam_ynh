<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Zusam untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/zusam)](https://ci-apps.yunohost.org/ci/apps/zusam/)
![Status kerja](https://apps.yunohost.org/badge/state/zusam)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/zusam)

[![Pasang Zusam dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zusam)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Zusam secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Zusam (/tsuˈzam/) is a free and open-source way to self-host private forums for groups of friends. Composed of a server written in PHP exposing a REST API and a lightweight webapp, Zusam is extensible and easy to install.
The goal is to make a stable, extensible, lightweight and user-friendly way to self-host private social groups.

### Features

- Links preview and embedded Youtube, Vimeo, Imgur, Soundcloud, Twitch, Bandcamp...
- Video and image upload
- Photo albums
- Public link generation for messages
- Completely responsive and mobile friendly
- Low server footprint


**Versi terkirim:** 0.5.6~ynh1

**Demo:** <https://demo.zusam.org>

## Tangkapan Layar

![Tangkapan Layar pada Zusam](./doc/screenshots/screenshot.jpg)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://zusam.org>
- Dokumentasi admin resmi: <https://github.com/zusam/zusam/tree/master/documentation>
- Depot kode aplikasi hulu: <https://github.com/zusam/zusam>
- Gudang YunoHost: <https://apps.yunohost.org/app/zusam>
- Laporkan bug: <https://github.com/YunoHost-Apps/zusam_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/zusam_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zusam_ynh/tree/testing --debug
atau
sudo yunohost app upgrade zusam -u https://github.com/YunoHost-Apps/zusam_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
