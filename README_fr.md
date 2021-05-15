# App exemple pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/REPLACEBYYOURAPP.svg)](https://dash.yunohost.org/appci/app/dataverse_ynh) ![](https://ci-apps.yunohost.org/ci/badges/dataverse_ynh.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/dataverse_ynh.maintain.svg)  
[![Installer Dataverse avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dataverse)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Dataverse rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Description rapide de cette application.

**Version incluse :** 1.0

## Captures d'écran

![https://i.imgur.com/QhBb2Xo.png](Lien vers une capture d'écran de cette application.)

## Démo

* [Démo officielle](https://demo.dataverse.org)

## Configuration

Comment configurer cette application : via le panneau d'administration, un fichier brut en SSH ou tout autre moyen.

## Documentation

 * Documentation officielle : https://guides.dataverse.org/en/latest/
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ?
* L'application peut-elle être utilisée par plusieurs utilisateurs ?

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/dataverse_ynh.svg)](https://ci-apps.yunohost.org/ci/apps/dataverse_ynh/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/dataverse_ynh.svg)](https://ci-apps-arm.yunohost.org/ci/apps/dataverse_ynh/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

**Plus d'informations sur la page de documentation :**  
https://yunohost.org/packaging_apps

## Liens

 * Signaler un bug : https://github.com/floriandierickx/dataverse_ynh/issues
 * Site de l'application : Lien vers le site officiel de cette application.
 * Dépôt de l'application principale : Lien vers le dépôt officiel de l'application principale.
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

**Seulement si vous voulez utiliser une branche de test pour le codage, au lieu de fusionner directement dans la banche principale.**
Merci de faire vos pull request sur la [branche testing](https://github.com/floriandierickx/dataverse_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/floriandierickx/dataverse_ynh/tree/testing --debug
ou
sudo yunohost app upgrade REPLACEBYYOURAPP -u https://github.com/floriandierickx/dataverse_ynh/tree/testing --debug
```
