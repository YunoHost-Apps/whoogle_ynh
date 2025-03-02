<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Whoogle pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/whoogle)](https://ci-apps.yunohost.org/ci/apps/whoogle/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/whoogle)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/whoogle)

[![Installer Whoogle avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=whoogle)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Whoogle rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Obtenez des résultats de recherche Google, mais sans aucune publicité, JavaScript, liens AMP, cookies ou suivi d'adresse IP. Facilement déployable en un clic en tant qu'application Docker et personnalisable avec un seul fichier de configuration. Rapide et simple à mettre en œuvre en tant que remplacement de moteur de recherche principal sur ordinateur et mobile.

### Fonctionnalités

- Pas de publicités ni de contenu sponsorisé
- Pas de JavaScript*
- Pas de cookies**
- Pas de suivi/liaison de votre adresse IP personnelle***
- Pas de liens AMP
- Pas de balises de suivi d'URL (c'est-à-dire utm=%s)
- Pas d'en-tête de référence
- Prise en charge des proxys Tor et HTTP/SOCKS
- Saisie semi-automatique/suggestions de recherche
- Recherches et suggestions de requêtes POST (lorsque cela est possible)
- Afficher les images en pleine résolution sans redirection de site (actuellement mobile uniquement)
- Modes de thème clair/foncé/système (avec prise en charge de la thématique CSS personnalisée)
- Agent utilisateur généré aléatoirement
- Recherches de style DDG (c'est-à-dire !<tag> <query>)
- Bangs personnalisés définis par l'utilisateur
- Recherche facultative basée sur la localisation (c'est-à-dire résultats à proximité de <ville>)
- Mode NoJS facultatif pour afficher les résultats de la recherche dans une fenêtre séparée avec JavaScript bloqué


**Version incluse :** 0.9.3~ynh1

## Captures d’écran

![Capture d’écran de Whoogle](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Dépôt de code officiel de l’app : <https://github.com/benbusby/whoogle-search>
- YunoHost Store : <https://apps.yunohost.org/app/whoogle>
- Signaler un bug : <https://github.com/YunoHost-Apps/whoogle_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing --debug
ou
sudo yunohost app upgrade whoogle -u https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
