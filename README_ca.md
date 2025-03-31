<!--
N.B.: Aquest README ha estat generat automàticament per <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NO s'ha de modificar manualment.
-->

# WatchYourLAN per YunoHost

[![Nivell d'integració](https://apps.yunohost.org/badge/integration/watchyourlan)](https://ci-apps.yunohost.org/ci/apps/watchyourlan/)
![Estat de funcionament](https://apps.yunohost.org/badge/state/watchyourlan)
![Estat de manteniment](https://apps.yunohost.org/badge/maintained/watchyourlan)

[![Instal·la WatchYourLAN amb YunoHosth](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchyourlan)

*[Llegeix aquest README en altres idiomes.](./ALL_README.md)*

> *Aquest paquet et permet instal·lar WatchYourLAN de forma ràpida i senzilla en un servidor YunoHost.*  
> *Si no tens YunoHost, consulta [la guia](https://yunohost.org/install) per saber com instal·lar-lo.*

## Visió general

Lightweight network IP scanner with web GUI.

### Features

- end notification when new host is found
- Monitor hosts online/offline history
- Keep a list of all hosts in the network
- Send data to InfluxDB2 to make a Grafana dashboard


**Versió inclosa:** 2.1.2~ynh1

## Captures de pantalla

![Captures de pantalla de WatchYourLAN](./doc/screenshots/Screenshot.png)

## Documentació i recursos

- Documentació oficial per l'administrador: <https://github.com/aceberg/WatchYourLAN/blob/main/docs/VLAN_ARP_SCAN.md>
- Repositori oficial del codi de l'aplicació: <https://github.com/aceberg/WatchYourLAN>
- Botiga YunoHost: <https://apps.yunohost.org/app/watchyourlan>
- Reportar un error: <https://github.com/YunoHost-Apps/watchyourlan_ynh/issues>

## Informació per a desenvolupadors

Envieu les pull request a la [branca `testing`](https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing).

Per provar la branca `testing`, procedir com descrit a continuació:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
o
sudo yunohost app upgrade watchyourlan -u https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
```

**Més informació sobre l'empaquetatge d'aplicacions:** <https://yunohost.org/packaging_apps>
