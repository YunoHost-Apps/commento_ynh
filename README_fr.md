<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Commento pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/commento.svg)](https://dash.yunohost.org/appci/app/commento) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/commento.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/commento.maintain.svg)

[![Installer Commento avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=commento)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Commento rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Commento++ vous permet de favoriser la discussion sur votre site Web – si vous avez un blog, vous pouvez intégrer Commento si vous souhaitez que vos lecteurs ajoutent des commentaires. Il possède une interface moderne et sécurisé. Contrairement à la plupart des alternatives, Commento est léger et axé sur la confidentialité.

### Caractéristiques

- Prise en charge des démarques
- Importer depuis Disqus
- Vote
- Détection automatisée du spam (intégration Askimet)
- Outils de modération
- Commentaires
- Rechargement à chaud des commentaires
- Notifications par e-mail.

**Version incluse :** 1.8.7~ynh3

**Démo :** <https://demo.souradip.com/chat.html>

## Captures d’écran

![Capture d’écran de Commento](./doc/screenshots/Screenshot.png)

## :red_circle: Anti-fonctionnalités

- **Application non maintenue **: Ce logiciel n'est plus maintenu. Attendez-vous à ce qu'il ne fonctionne plus avec le temps, et que l'on découvre des failles de sécurité qui ne seront pas corrigées, etc.

## Documentations et ressources

- Site officiel de l’app : <https://commento.io/>
- Documentation officielle de l’admin : <https://docs.commento.io/>
- Dépôt de code officiel de l’app : <https://github.com/souramoo/commentoplusplus>
- YunoHost Store : <https://apps.yunohost.org/app/commento>
- Signaler un bug : <https://github.com/YunoHost-Apps/commento_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/commento_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/commento_ynh/tree/testing --debug
ou
sudo yunohost app upgrade commento -u https://github.com/YunoHost-Apps/commento_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
