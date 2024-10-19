<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# WatchYourLAN voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/watchyourlan.svg)](https://ci-apps.yunohost.org/ci/apps/watchyourlan/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/watchyourlan.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/watchyourlan.maintain.svg)

[![WatchYourLAN met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchyourlan)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je WatchYourLAN snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Lightweight network IP scanner with web GUI. Features:


### Features

- end notification when new host is found
- Monitor hosts online/offline history
- Keep a list of all hosts in the network
- Send data to InfluxDB2 to make a Grafana dashboard


**Geleverde versie:** 2.0.3~ynh1

## Schermafdrukken

![Schermafdrukken van WatchYourLAN](./doc/screenshots/Screenshot.png)

## Documentatie en bronnen

- Upstream app codedepot: <https://github.com/aceberg/WatchYourLAN>
- YunoHost-store: <https://apps.yunohost.org/app/watchyourlan>
- Meld een bug: <https://github.com/YunoHost-Apps/watchyourlan_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
of
sudo yunohost app upgrade watchyourlan -u https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
