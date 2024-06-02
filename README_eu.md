<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Commento YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/commento.svg)](https://dash.yunohost.org/appci/app/commento) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/commento.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/commento.maintain.svg)

[![Instalatu Commento YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=commento)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Commento YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

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


**Paketatutako bertsioa:** 1.8.7~ynh2

**Demoa:** <https://demo.souradip.com/chat.html>

## Pantaila-argazkiak

![Commento(r)en pantaila-argazkia](./doc/screenshots/Screenshot.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizko garapena utzita**: Software honek ez du arduradunik. Denborak aurrera egin ahala funtzionatzeari utziko dio, konpondu gabeko segurtasun arazoak izango ditu, etab.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://commento.io/>
- Administratzaileen dokumentazio ofiziala: <https://docs.commento.io/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/souramoo/commentoplusplus>
- YunoHost Denda: <https://apps.yunohost.org/app/commento>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/commento_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/commento_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/commento_ynh/tree/testing --debug
edo
sudo yunohost app upgrade commento -u https://github.com/YunoHost-Apps/commento_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
