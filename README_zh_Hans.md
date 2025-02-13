<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 WatchYourLAN

[![集成程度](https://apps.yunohost.org/badge/integration/watchyourlan)](https://ci-apps.yunohost.org/ci/apps/watchyourlan/)
![工作状态](https://apps.yunohost.org/badge/state/watchyourlan)
![维护状态](https://apps.yunohost.org/badge/maintained/watchyourlan)

[![使用 YunoHost 安装 WatchYourLAN](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchyourlan)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 WatchYourLAN。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Lightweight network IP scanner with web GUI.

### Features

- end notification when new host is found
- Monitor hosts online/offline history
- Keep a list of all hosts in the network
- Send data to InfluxDB2 to make a Grafana dashboard


**分发版本：** 2.0.4~ynh1

## 截图

![WatchYourLAN 的截图](./doc/screenshots/Screenshot.png)

## 文档与资源

- 官方管理文档： <https://github.com/aceberg/WatchYourLAN/blob/main/docs/VLAN_ARP_SCAN.md>
- 上游应用代码库： <https://github.com/aceberg/WatchYourLAN>
- YunoHost 商店： <https://apps.yunohost.org/app/watchyourlan>
- 报告 bug： <https://github.com/YunoHost-Apps/watchyourlan_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
或
sudo yunohost app upgrade watchyourlan -u https://github.com/YunoHost-Apps/watchyourlan_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
