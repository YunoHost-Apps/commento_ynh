<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Commento para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/commento.svg)](https://dash.yunohost.org/appci/app/commento) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/commento.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/commento.maintain.svg)

[![Instalar Commento con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=commento)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarCommento rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

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


**Versión actual:** 1.8.7~ynh3

**Demo:** <https://demo.souradip.com/chat.html>

## Capturas

![Captura de Commento](./doc/screenshots/Screenshot.png)

## :red_circle: funcionalidades no deseadas

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentaciones y recursos

- Sitio web oficial: <https://commento.io/>
- Documentación administrador oficial: <https://docs.commento.io/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/souramoo/commentoplusplus>
- Catálogo YunoHost: <https://apps.yunohost.org/app/commento>
- Reportar un error: <https://github.com/YunoHost-Apps/commento_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/commento_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/commento_ynh/tree/testing --debug
o
sudo yunohost app upgrade commento -u https://github.com/YunoHost-Apps/commento_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
