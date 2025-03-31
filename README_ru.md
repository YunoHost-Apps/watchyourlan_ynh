<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# WatchYourLAN для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/watchyourlan)](https://ci-apps.yunohost.org/ci/apps/watchyourlan/)
![Состояние работы](https://apps.yunohost.org/badge/state/watchyourlan)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/watchyourlan)

[![Установите WatchYourLAN с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchyourlan)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить WatchYourLAN быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Lightweight network IP scanner with web GUI.

### Features

- end notification when new host is found
- Monitor hosts online/offline history
- Keep a list of all hosts in the network
- Send data to InfluxDB2 to make a Grafana dashboard


**Поставляемая версия:** 2.1.2~ynh1

## Снимки экрана

![Снимок экрана WatchYourLAN](./doc/screenshots/Screenshot.png)

## Документация и ресурсы

- Официальная документация администратора: <https://github.com/aceberg/WatchYourLAN/blob/main/docs/VLAN_ARP_SCAN.md>
- Репозиторий кода главной ветки приложения: <https://github.com/aceberg/WatchYourLAN>
- Магазин YunoHost: <https://apps.yunohost.org/app/watchyourlan>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/watchyourlan_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
или
sudo yunohost app upgrade watchyourlan -u https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
