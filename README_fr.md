<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Gokapi pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/gokapi.svg)](https://ci-apps.yunohost.org/ci/apps/gokapi/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/gokapi.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/gokapi.maintain.svg)

[![Installer Gokapi avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gokapi)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Gokapi rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Gokapi est un serveur léger de partage de fichiers, qui expire après un certain nombre de téléchargements ou de jours. Il est similaire à Firefox Send, à la différence que seul l'administrateur est autorisé à télécharger des fichiers.

**Version incluse :** 1.9.2~ynh1

## Captures d’écran

![Capture d’écran de Gokapi](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Documentation officielle de l’admin : <https://gokapi.readthedocs.io/>
- Dépôt de code officiel de l’app : <https://github.com/Forceu/Gokapi>
- YunoHost Store : <https://apps.yunohost.org/app/gokapi>
- Signaler un bug : <https://github.com/YunoHost-Apps/gokapi_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/gokapi_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gokapi_ynh/tree/testing --debug
ou
sudo yunohost app upgrade gokapi -u https://github.com/YunoHost-Apps/gokapi_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
