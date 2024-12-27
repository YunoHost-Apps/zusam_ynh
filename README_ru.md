<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Zusam для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/zusam)](https://ci-apps.yunohost.org/ci/apps/zusam/)
![Состояние работы](https://apps.yunohost.org/badge/state/zusam)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/zusam)

[![Установите Zusam с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zusam)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Zusam быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Zusam (/tsuˈzam/) is a free and open-source way to self-host private forums for groups of friends. Composed of a server written in PHP exposing a REST API and a lightweight webapp, Zusam is extensible and easy to install.
The goal is to make a stable, extensible, lightweight and user-friendly way to self-host private social groups.

### Features

- Links preview and embedded Youtube, Vimeo, Imgur, Soundcloud, Twitch, Bandcamp...
- Video and image upload
- Photo albums
- Public link generation for messages
- Completely responsive and mobile friendly
- Low server footprint


**Поставляемая версия:** 0.5.6~ynh1

**Демо-версия:** <https://demo.zusam.org>

## Снимки экрана

![Снимок экрана Zusam](./doc/screenshots/screenshot.jpg)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://zusam.org>
- Официальная документация администратора: <https://github.com/zusam/zusam/tree/master/documentation>
- Репозиторий кода главной ветки приложения: <https://github.com/zusam/zusam>
- Магазин YunoHost: <https://apps.yunohost.org/app/zusam>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/zusam_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/zusam_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zusam_ynh/tree/testing --debug
или
sudo yunohost app upgrade zusam -u https://github.com/YunoHost-Apps/zusam_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
