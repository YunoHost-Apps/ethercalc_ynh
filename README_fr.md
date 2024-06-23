<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# EtherCalc pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/ethercalc.svg)](https://dash.yunohost.org/appci/app/ethercalc) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/ethercalc.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/ethercalc.maintain.svg)

[![Installer EtherCalc avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ethercalc)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer EtherCalc rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

EtherCalc est un tableur collaboratif éditable en temps réel. Chaque tableur possède sa propre URL. Il dispose des fonctionnalités de base : mise en forme, fonctions mathématiques, graphiques, ajout de commentaires, historique des versions, export en HTML ou en CSV. EtherCalc est un logiciel décentralisé : différentes instances permettent d'utiliser le service, elles sont mises à disposition par plusieurs organisations (par exemple le site éponyme ou le service FramaCalc). Cela permet d'éviter de concentrer toutes les données entre les mains d'un même acteur. Les instances peuvent être personnalisées (limitation de la durée d'hébergement du tableur, modification du design, etc.).


**Version incluse :** 20240101~ynh1

**Démo :** <https://ethercalc.net/>

## Captures d’écran

![Capture d’écran de EtherCalc](./doc/screenshots/screenshot.png)

## :red_circle: Anti-fonctionnalités

- **Application non maintenue **: Ce logiciel n'est plus maintenu. Attendez-vous à ce qu'il ne fonctionne plus avec le temps, et que l'on découvre des failles de sécurité qui ne seront pas corrigées, etc.

## Documentations et ressources

- Site officiel de l’app : <https://ethercalc.net/>
- Dépôt de code officiel de l’app : <https://github.com/audreyt/ethercalc>
- YunoHost Store : <https://apps.yunohost.org/app/ethercalc>
- Signaler un bug : <https://github.com/YunoHost-Apps/ethercalc_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/ethercalc_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ethercalc_ynh/tree/testing --debug
ou
sudo yunohost app upgrade ethercalc -u https://github.com/YunoHost-Apps/ethercalc_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
