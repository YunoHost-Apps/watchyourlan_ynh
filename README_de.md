<!--
N.B.: Diese README wurde automatisch von <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> generiert.
Sie darf NICHT von Hand bearbeitet werden.
-->

# WatchYourLAN für YunoHost

[![Integrations-Level](https://apps.yunohost.org/badge/integration/watchyourlan)](https://ci-apps.yunohost.org/ci/apps/watchyourlan/)
![Funktionsstatus](https://apps.yunohost.org/badge/state/watchyourlan)
![Wartungsstatus](https://apps.yunohost.org/badge/maintained/watchyourlan)

[![WatchYourLAN mit YunoHost installieren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchyourlan)

*[Dieses README in anderen Sprachen lesen.](./ALL_README.md)*

> *Mit diesem Paket können Sie WatchYourLAN schnell und einfach auf einem YunoHost-Server installieren.*  
> *Wenn Sie YunoHost nicht haben, lesen Sie bitte [die Anleitung](https://yunohost.org/install), um zu erfahren, wie Sie es installieren.*

## Übersicht

Lightweight network IP scanner with web GUI.

### Features

- end notification when new host is found
- Monitor hosts online/offline history
- Keep a list of all hosts in the network
- Send data to InfluxDB2 to make a Grafana dashboard


**Ausgelieferte Version:** 2.1.1~ynh1

## Bildschirmfotos

![Bildschirmfotos von WatchYourLAN](./doc/screenshots/Screenshot.png)

## Dokumentation und Ressourcen

- Offizielle Verwaltungsdokumentation: <https://github.com/aceberg/WatchYourLAN/blob/main/docs/VLAN_ARP_SCAN.md>
- Upstream App Repository: <https://github.com/aceberg/WatchYourLAN>
- YunoHost-Shop: <https://apps.yunohost.org/app/watchyourlan>
- Einen Fehler melden: <https://github.com/YunoHost-Apps/watchyourlan_ynh/issues>

## Entwicklerinformationen

Bitte senden Sie Ihren Pull-Request an den [`testing` branch](https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing).

Um den `testing` Branch auszuprobieren, gehen Sie bitte wie folgt vor:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
oder
sudo yunohost app upgrade watchyourlan -u https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
```

**Weitere Informationen zur App-Paketierung:** <https://yunohost.org/packaging_apps>
