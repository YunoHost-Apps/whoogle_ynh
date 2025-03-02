<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Whoogle para YunoHost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/whoogle)](https://ci-apps.yunohost.org/ci/apps/whoogle/)
![Estado de funcionamento](https://apps.yunohost.org/badge/state/whoogle)
![Estado de mantemento](https://apps.yunohost.org/badge/maintained/whoogle)

[![Instalar Whoogle con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=whoogle)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Whoogle de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

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


**Versión proporcionada:** 0.9.3~ynh1

## Capturas de pantalla

![Captura de pantalla de Whoogle](./doc/screenshots/screenshot.png)

## Documentación e recursos

- Repositorio de orixe do código: <https://github.com/benbusby/whoogle-search>
- Tenda YunoHost: <https://apps.yunohost.org/app/whoogle>
- Informar dun problema: <https://github.com/YunoHost-Apps/whoogle_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing --debug
ou
sudo yunohost app upgrade whoogle -u https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
