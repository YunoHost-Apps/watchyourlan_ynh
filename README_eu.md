<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# WatchYourLAN YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/watchyourlan.svg)](https://ci-apps.yunohost.org/ci/apps/watchyourlan/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/watchyourlan.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/watchyourlan.maintain.svg)

[![Instalatu WatchYourLAN YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchyourlan)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek WatchYourLAN YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Lightweight network IP scanner with web GUI.

### Features

- end notification when new host is found
- Monitor hosts online/offline history
- Keep a list of all hosts in the network
- Send data to InfluxDB2 to make a Grafana dashboard


**Paketatutako bertsioa:** 2.0.3~ynh1

## Pantaila-argazkiak

![WatchYourLAN(r)en pantaila-argazkia](./doc/screenshots/Screenshot.png)

## Dokumentazioa eta baliabideak

- Administratzaileen dokumentazio ofiziala: <https://github.com/aceberg/WatchYourLAN/blob/main/docs/VLAN_ARP_SCAN.md>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/aceberg/WatchYourLAN>
- YunoHost Denda: <https://apps.yunohost.org/app/watchyourlan>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/watchyourlan_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
edo
sudo yunohost app upgrade watchyourlan -u https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
