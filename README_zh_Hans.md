<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 EtherCalc

[![集成程度](https://dash.yunohost.org/integration/ethercalc.svg)](https://dash.yunohost.org/appci/app/ethercalc) ![工作状态](https://ci-apps.yunohost.org/ci/badges/ethercalc.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/ethercalc.maintain.svg)

[![使用 YunoHost 安装 EtherCalc](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ethercalc)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 EtherCalc。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

EtherCalc is a collaborative spreadsheet that can be edited in real time. Each spreadsheet has its own URL. It has the basic functionalities: formatting, mathematical functions, graphics, adding comments, version history, export in HTML or in CSV. EtherCalc is a decentralized software: different instances allow the use of the service, they are made available by several organizations (for example the eponymous site or the FramaCalc service). This makes it possible to avoid concentrating all the data in the hands of the same actor. Instances can be personalized (limitation of the duration of hosting of the spreadsheet, modification of the design, etc.).

**分发版本：** 20240101~ynh1

**演示：** <https://ethercalc.net/>

## 截图

![EtherCalc 的截图](./doc/screenshots/screenshot.png)

## :red_circle: 负面特征

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## 文档与资源

- 官方应用网站： <https://ethercalc.net/>
- 上游应用代码库： <https://github.com/audreyt/ethercalc>
- YunoHost 商店： <https://apps.yunohost.org/app/ethercalc>
- 报告 bug： <https://github.com/YunoHost-Apps/ethercalc_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/ethercalc_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ethercalc_ynh/tree/testing --debug
或
sudo yunohost app upgrade ethercalc -u https://github.com/YunoHost-Apps/ethercalc_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
