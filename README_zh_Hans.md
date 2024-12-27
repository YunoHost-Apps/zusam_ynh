<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Zusam

[![集成程度](https://apps.yunohost.org/badge/integration/zusam)](https://ci-apps.yunohost.org/ci/apps/zusam/)
![工作状态](https://apps.yunohost.org/badge/state/zusam)
![维护状态](https://apps.yunohost.org/badge/maintained/zusam)

[![使用 YunoHost 安装 Zusam](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zusam)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Zusam。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Zusam (/tsuˈzam/) is a free and open-source way to self-host private forums for groups of friends. Composed of a server written in PHP exposing a REST API and a lightweight webapp, Zusam is extensible and easy to install.
The goal is to make a stable, extensible, lightweight and user-friendly way to self-host private social groups.

### Features

- Links preview and embedded Youtube, Vimeo, Imgur, Soundcloud, Twitch, Bandcamp...
- Video and image upload
- Photo albums
- Public link generation for messages
- Completely responsive and mobile friendly
- Low server footprint


**分发版本：** 0.5.6~ynh1

**演示：** <https://demo.zusam.org>

## 截图

![Zusam 的截图](./doc/screenshots/screenshot.jpg)

## 文档与资源

- 官方应用网站： <https://zusam.org>
- 官方管理文档： <https://github.com/zusam/zusam/tree/master/documentation>
- 上游应用代码库： <https://github.com/zusam/zusam>
- YunoHost 商店： <https://apps.yunohost.org/app/zusam>
- 报告 bug： <https://github.com/YunoHost-Apps/zusam_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/zusam_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zusam_ynh/tree/testing --debug
或
sudo yunohost app upgrade zusam -u https://github.com/YunoHost-Apps/zusam_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
