# App exemple pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/deplacement-covid-19.svg)](https://dash.yunohost.org/appci/app/deplacement-covid-19)  
[![Installer deplacement-covid-19 avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=deplacement-covid-19)

> *Ce package vous permet d'installer deplacement-covid-19_ynh rapidement et simplement sur un serveur Yunohost.  
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble
Générateur de certificat de déplacement.

**Version incluse:** 0.0.1

#### Architectures supportées

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/deplacement-covid-19%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/deplacement-covid-19/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/deplacement-covid-19%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/deplacement-covid-19/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/deplacement-covid-19%20%28Apps%29.svg)](https://ci-stretch.nohost.me/ci/apps/deplacement-covid-19/)

## Bug

 * La conf nginx ne semble pas prise en compte, il faut ajouter index.html en fin d'url...

## TODOs

 * Remplissage auto des infos personnels (dans LDAP ?)
 * Pousser l'attestation dans NextCloud

## Liens

 * Signaler un bug: https://github.com/YunoHost-Apps/deplacement-covid-19_ynh/issues
 * Site de l'application: Lien vers le site officiel de cette application
 * Dépôt de l'application principale: Lien vers le dépôt officiel de l'application principale
 * Site web YunoHost: https://yunohost.org/

---

Informations pour les développeurs
----------------

**Seulement si vous voulez utiliser une branche de test pour le codage, au lieu de fusionner directement dans la banche principale.**
Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/deplacement-covid-19_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/deplacement-covid-19_ynh/tree/testing --debug
ou
sudo yunohost app upgrade deplacement-covid-19 -u https://github.com/YunoHost-Apps/deplacement-covid-19_ynh/tree/testing --debug
```
