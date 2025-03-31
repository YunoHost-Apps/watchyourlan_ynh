<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# WatchYourLAN para YunoHost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/watchyourlan)](https://ci-apps.yunohost.org/ci/apps/watchyourlan/)
![Estado funcional](https://apps.yunohost.org/badge/state/watchyourlan)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/watchyourlan)

[![Instalar WatchYourLAN con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchyourlan)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarWatchYourLAN rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Lightweight network IP scanner with web GUI.

### Features

- end notification when new host is found
- Monitor hosts online/offline history
- Keep a list of all hosts in the network
- Send data to InfluxDB2 to make a Grafana dashboard


**Versión actual:** 2.1.2~ynh1

## Capturas

![Captura de WatchYourLAN](./doc/screenshots/Screenshot.png)

## Documentaciones y recursos

- Documentación administrador oficial: <https://github.com/aceberg/WatchYourLAN/blob/main/docs/VLAN_ARP_SCAN.md>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/aceberg/WatchYourLAN>
- Catálogo YunoHost: <https://apps.yunohost.org/app/watchyourlan>
- Reportar un error: <https://github.com/YunoHost-Apps/watchyourlan_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
o
sudo yunohost app upgrade watchyourlan -u https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
