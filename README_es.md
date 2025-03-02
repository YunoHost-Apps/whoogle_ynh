<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Whoogle para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/whoogle)](https://ci-apps.yunohost.org/ci/apps/whoogle/)
![Estado funcional](https://apps.yunohost.org/badge/state/whoogle)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/whoogle)

[![Instalar Whoogle con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=whoogle)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarWhoogle rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

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


**Versión actual:** 0.9.3~ynh1

## Capturas

![Captura de Whoogle](./doc/screenshots/screenshot.png)

## Documentaciones y recursos

- Repositorio del código fuente oficial de la aplicación : <https://github.com/benbusby/whoogle-search>
- Catálogo YunoHost: <https://apps.yunohost.org/app/whoogle>
- Reportar un error: <https://github.com/YunoHost-Apps/whoogle_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing --debug
o
sudo yunohost app upgrade whoogle -u https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
