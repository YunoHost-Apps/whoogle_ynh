<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Whoogle

[![集成程度](https://apps.yunohost.org/badge/integration/whoogle)](https://ci-apps.yunohost.org/ci/apps/whoogle/)
![工作状态](https://apps.yunohost.org/badge/state/whoogle)
![维护状态](https://apps.yunohost.org/badge/maintained/whoogle)

[![使用 YunoHost 安装 Whoogle](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=whoogle)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Whoogle。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Get Google search results, but without any ads, JavaScript, AMP links, cookies, or IP address tracking. Easily deployable in one click as a Docker app, and customizable with a single config file. Quick and simple to implement as a primary search engine replacement on both desktop and mobile.

### Features

- No ads or sponsored content
- No JavaScript*
- No cookies**
- No tracking/linking of your personal IP address***
- No AMP links
- No URL tracking tags (i.e. utm=%s)
- No referrer header
- Tor and HTTP/SOCKS proxy support
- Autocomplete/search suggestions
- POST request search and suggestion queries (when possible)
- View images at full res without site redirect (currently mobile only)
- Light/Dark/System theme modes (with support for custom CSS theming)
- Randomly generated User Agent
- DDG-style bang (i.e. !<tag> <query>) searches
- User-defined custom bangs
- Optional location-based searching (i.e. results near <city>)
- Optional NoJS mode to view search results in a separate window with JavaScript blocked


**分发版本：** 0.9.3~ynh1

## 截图

![Whoogle 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 上游应用代码库： <https://github.com/benbusby/whoogle-search>
- YunoHost 商店： <https://apps.yunohost.org/app/whoogle>
- 报告 bug： <https://github.com/YunoHost-Apps/whoogle_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing --debug
或
sudo yunohost app upgrade whoogle -u https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
