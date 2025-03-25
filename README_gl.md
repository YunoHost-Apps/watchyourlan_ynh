<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# WatchYourLAN para YunoHost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/watchyourlan)](https://ci-apps.yunohost.org/ci/apps/watchyourlan/)
![Estado de funcionamento](https://apps.yunohost.org/badge/state/watchyourlan)
![Estado de mantemento](https://apps.yunohost.org/badge/maintained/watchyourlan)

[![Instalar WatchYourLAN con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchyourlan)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar WatchYourLAN de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Lightweight network IP scanner with web GUI.

### Features

- end notification when new host is found
- Monitor hosts online/offline history
- Keep a list of all hosts in the network
- Send data to InfluxDB2 to make a Grafana dashboard


**Versión proporcionada:** 2.1.1~ynh1

## Capturas de pantalla

![Captura de pantalla de WatchYourLAN](./doc/screenshots/Screenshot.png)

## Documentación e recursos

- Documentación oficial para admin: <https://github.com/aceberg/WatchYourLAN/blob/main/docs/VLAN_ARP_SCAN.md>
- Repositorio de orixe do código: <https://github.com/aceberg/WatchYourLAN>
- Tenda YunoHost: <https://apps.yunohost.org/app/watchyourlan>
- Informar dun problema: <https://github.com/YunoHost-Apps/watchyourlan_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
ou
sudo yunohost app upgrade watchyourlan -u https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
