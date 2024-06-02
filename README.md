<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Commento for YunoHost

[![Integration level](https://dash.yunohost.org/integration/commento.svg)](https://dash.yunohost.org/appci/app/commento) ![Working status](https://ci-apps.yunohost.org/ci/badges/commento.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/commento.maintain.svg)

[![Install Commento with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=commento)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Commento quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Commento++ allows you to foster discussion on your website – if you have a blog, you can embed Commento if you want your readers to add comments. It's fast and bloat-free, has a modern interface, and is reasonably secure. Unlike most alternatives, Commento is lightweight and privacy-focused.

### Features

- Markdown support
- Import from Disqus
- Voting
- Automated spam detection (Askimet integration)
- Moderation tools
- Sticky comments
- Thread locking
- Hot-reloading of comments
- Email notifications.


**Shipped version:** 1.8.7~ynh3

**Demo:** <https://demo.souradip.com/chat.html>

## Screenshots

![Screenshot of Commento](./doc/screenshots/Screenshot.png)

## :red_circle: Antifeatures

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentation and resources

- Official app website: <https://commento.io/>
- Official admin documentation: <https://docs.commento.io/>
- Upstream app code repository: <https://github.com/souramoo/commentoplusplus>
- YunoHost Store: <https://apps.yunohost.org/app/commento>
- Report a bug: <https://github.com/YunoHost-Apps/commento_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/commento_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/commento_ynh/tree/testing --debug
or
sudo yunohost app upgrade commento -u https://github.com/YunoHost-Apps/commento_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
