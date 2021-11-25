<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Commento for YunoHost

[![Integration level](https://dash.yunohost.org/integration/commento.svg)](https://dash.yunohost.org/appci/app/commento) ![](https://ci-apps.yunohost.org/ci/badges/commento.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/commento.maintain.svg)  
[![Install Commento with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=commento)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Commento quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Commento allows you to foster discussion on your website – if you have a blog, you can embed Commento if you want your readers to add comments. It's fast and bloat-free, has a modern interface, and is reasonably secure. Unlike most alternatives, Commento is lightweight and privacy-focused; I'll never sell your data, show ads, embed third-party tracking scripts, or inject affiliate links.

### Features

- Moderation tools
- Markdown formatting
- Nested replies
- No sign-up required
- Spam detection
- Sticky comments
- Upvotes and downvotes


**Shipped version:** 1.8.0~ynh1

**Demo:** https://demo.commento.io/

## Screenshots

![](./doc/screenshots/Screenshot.png)

## Documentation and resources

* Official app website: https://commento.io/
* Official admin documentation: https://docs.commento.io/
* Upstream app code repository: https://gitlab.com/commento/commento
* YunoHost documentation for this app: https://yunohost.org/app_commento
* Report a bug: https://github.com/YunoHost-Apps/commento_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/commento_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/commento_ynh/tree/testing --debug
or
sudo yunohost app upgrade commento -u https://github.com/YunoHost-Apps/commento_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps