<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# WatchYourLAN pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/watchyourlan.svg)](https://ci-apps.yunohost.org/ci/apps/watchyourlan/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/watchyourlan.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/watchyourlan.maintain.svg)

[![Installer WatchYourLAN avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchyourlan)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer WatchYourLAN rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Scanner IP réseau léger avec interface graphique Web.

### Fonctionnalités

- notification de fin lorsqu'un nouvel hôte est trouvé
- Surveiller l'historique en ligne/hors ligne des hôtes
- Conserver une liste de tous les hôtes du réseau
- Envoyer des données à InfluxDB2 pour créer un tableau de bord Grafana

**Version incluse :** 2.0.3~ynh1

## Captures d’écran

![Capture d’écran de WatchYourLAN](./doc/screenshots/Screenshot.png)

## Documentations et ressources

- Documentation officielle de l’admin : <https://github.com/aceberg/WatchYourLAN/blob/main/docs/VLAN_ARP_SCAN.md>
- Dépôt de code officiel de l’app : <https://github.com/aceberg/WatchYourLAN>
- YunoHost Store : <https://apps.yunohost.org/app/watchyourlan>
- Signaler un bug : <https://github.com/YunoHost-Apps/watchyourlan_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
ou
sudo yunohost app upgrade watchyourlan -u https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
