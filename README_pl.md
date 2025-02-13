<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# WatchYourLAN dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/watchyourlan)](https://ci-apps.yunohost.org/ci/apps/watchyourlan/)
![Status działania](https://apps.yunohost.org/badge/state/watchyourlan)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/watchyourlan)

[![Zainstaluj WatchYourLAN z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchyourlan)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację WatchYourLAN na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

Lightweight network IP scanner with web GUI.

### Features

- end notification when new host is found
- Monitor hosts online/offline history
- Keep a list of all hosts in the network
- Send data to InfluxDB2 to make a Grafana dashboard


**Dostarczona wersja:** 2.0.3~ynh1

## Zrzuty ekranu

![Zrzut ekranu z WatchYourLAN](./doc/screenshots/Screenshot.png)

## Dokumentacja i zasoby

- Oficjalna dokumentacja dla administratora: <https://github.com/aceberg/WatchYourLAN/blob/main/docs/VLAN_ARP_SCAN.md>
- Repozytorium z kodem źródłowym: <https://github.com/aceberg/WatchYourLAN>
- Sklep YunoHost: <https://apps.yunohost.org/app/watchyourlan>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/watchyourlan_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
lub
sudo yunohost app upgrade watchyourlan -u https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
