<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Zusam para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/zusam.svg)](https://ci-apps.yunohost.org/ci/apps/zusam/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/zusam.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/zusam.maintain.svg)

[![Instalar Zusam con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zusam)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarZusam rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Zusam (/tsuˈzam/) is a free and open-source way to self-host private forums for groups of friends. Composed of a server written in PHP exposing a REST API and a lightweight webapp, Zusam is extensible and easy to install.
The goal is to make a stable, extensible, lightweight and user-friendly way to self-host private social groups.

### Features

- Links preview and embedded Youtube, Vimeo, Imgur, Soundcloud, Twitch, Bandcamp...
- Video and image upload
- Photo albums
- Public link generation for messages
- Completely responsive and mobile friendly
- Low server footprint


**Versión actual:** 0.5.6~ynh1

**Demo:** <https://demo.zusam.org>

## Capturas

![Captura de Zusam](./doc/screenshots/screenshot.jpg)

## Documentaciones y recursos

- Sitio web oficial: <https://zusam.org>
- Documentación administrador oficial: <https://github.com/zusam/zusam/tree/master/documentation>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/zusam/zusam>
- Catálogo YunoHost: <https://apps.yunohost.org/app/zusam>
- Reportar un error: <https://github.com/YunoHost-Apps/zusam_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/zusam_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zusam_ynh/tree/testing --debug
o
sudo yunohost app upgrade zusam -u https://github.com/YunoHost-Apps/zusam_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
