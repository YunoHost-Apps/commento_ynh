<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Commento para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/commento.svg)](https://dash.yunohost.org/appci/app/commento) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/commento.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/commento.maintain.svg)

[![Instalar Commento con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=commento)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Commento de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

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


**Versión proporcionada:** 1.8.7~ynh3

**Demo:** <https://demo.souradip.com/chat.html>

## Capturas de pantalla

![Captura de pantalla de Commento](./doc/screenshots/Screenshot.png)

## :red_circle: Debes considerar

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentación e recursos

- Web oficial da app: <https://commento.io/>
- Documentación oficial para admin: <https://docs.commento.io/>
- Repositorio de orixe do código: <https://github.com/souramoo/commentoplusplus>
- Tenda YunoHost: <https://apps.yunohost.org/app/commento>
- Informar dun problema: <https://github.com/YunoHost-Apps/commento_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/commento_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/commento_ynh/tree/testing --debug
ou
sudo yunohost app upgrade commento -u https://github.com/YunoHost-Apps/commento_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
