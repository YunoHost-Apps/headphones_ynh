# Headphones pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/headphones.svg)](https://dash.yunohost.org/appci/app/headphones) ![](https://ci-apps.yunohost.org/ci/badges/headphones.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/headphones.maintain.svg)  
[![Installer Headphones avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=headphones)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Headphones rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Headphones is an automated music downloader for NZB and Torrent, written in Python. It supports SABnzbd, NZBget, Transmission, µTorrent, Deluge and Blackhole.


**Version incluse :** 0.6.0~ynh1



## Captures d'écran

![](./doc/screenshots/screenshot01.png)

## Documentations et ressources

* Site officiel de l'app : https://github.com/rembo10/headphones
* Documentation officielle utilisateur : https://github.com/rembo10/headphones/wiki/Usage-guide
* Dépôt de code officiel de l'app : https://github.com/rembo10/headphones
* Documentation YunoHost pour cette app : https://yunohost.org/app_headphones
* Signaler un bug : https://github.com/YunoHost-Apps/headphones_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/headphones_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/headphones_ynh/tree/testing --debug
ou
sudo yunohost app upgrade headphones -u https://github.com/YunoHost-Apps/headphones_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps