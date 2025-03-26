<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# WatchYourLAN untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/watchyourlan)](https://ci-apps.yunohost.org/ci/apps/watchyourlan/)
![Status kerja](https://apps.yunohost.org/badge/state/watchyourlan)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/watchyourlan)

[![Pasang WatchYourLAN dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchyourlan)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang WatchYourLAN secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Lightweight network IP scanner with web GUI.

### Features

- end notification when new host is found
- Monitor hosts online/offline history
- Keep a list of all hosts in the network
- Send data to InfluxDB2 to make a Grafana dashboard


**Versi terkirim:** 2.1.1~ynh1

## Tangkapan Layar

![Tangkapan Layar pada WatchYourLAN](./doc/screenshots/Screenshot.png)

## Dokumentasi dan sumber daya

- Dokumentasi admin resmi: <https://github.com/aceberg/WatchYourLAN/blob/main/docs/VLAN_ARP_SCAN.md>
- Depot kode aplikasi hulu: <https://github.com/aceberg/WatchYourLAN>
- Gudang YunoHost: <https://apps.yunohost.org/app/watchyourlan>
- Laporkan bug: <https://github.com/YunoHost-Apps/watchyourlan_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
atau
sudo yunohost app upgrade watchyourlan -u https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
