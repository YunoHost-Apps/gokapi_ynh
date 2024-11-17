<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Gokapi

[![集成程度](https://dash.yunohost.org/integration/gokapi.svg)](https://ci-apps.yunohost.org/ci/apps/gokapi/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/gokapi.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/gokapi.maintain.svg)

[![使用 YunoHost 安装 Gokapi](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gokapi)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Gokapi。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Gokapi is a lightweight server to share files, which expire after a set amount of downloads or days. It is similar to the discontinued Firefox Send, with the difference that only the admin is allowed to upload files.

**分发版本：** 1.9.2~ynh1

## 截图

![Gokapi 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方管理文档： <https://gokapi.readthedocs.io/>
- 上游应用代码库： <https://github.com/Forceu/Gokapi>
- YunoHost 商店： <https://apps.yunohost.org/app/gokapi>
- 报告 bug： <https://github.com/YunoHost-Apps/gokapi_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/gokapi_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gokapi_ynh/tree/testing --debug
或
sudo yunohost app upgrade gokapi -u https://github.com/YunoHost-Apps/gokapi_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>