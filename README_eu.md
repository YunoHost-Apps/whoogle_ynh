<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Whoogle YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/whoogle)](https://ci-apps.yunohost.org/ci/apps/whoogle/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/whoogle)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/whoogle)

[![Instalatu Whoogle YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=whoogle)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Whoogle YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

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


**Paketatutako bertsioa:** 0.9.3~ynh1

## Pantaila-argazkiak

![Whoogle(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/benbusby/whoogle-search>
- YunoHost Denda: <https://apps.yunohost.org/app/whoogle>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/whoogle_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing --debug
edo
sudo yunohost app upgrade whoogle -u https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
