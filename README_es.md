<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# EtherCalc para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/ethercalc.svg)](https://dash.yunohost.org/appci/app/ethercalc) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/ethercalc.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/ethercalc.maintain.svg)

[![Instalar EtherCalc con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ethercalc)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarEtherCalc rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

EtherCalc is a collaborative spreadsheet that can be edited in real time. Each spreadsheet has its own URL. It has the basic functionalities: formatting, mathematical functions, graphics, adding comments, version history, export in HTML or in CSV. EtherCalc is a decentralized software: different instances allow the use of the service, they are made available by several organizations (for example the eponymous site or the FramaCalc service). This makes it possible to avoid concentrating all the data in the hands of the same actor. Instances can be personalized (limitation of the duration of hosting of the spreadsheet, modification of the design, etc.).

**Versión actual:** 20240101~ynh1

**Demo:** <https://ethercalc.net/>

## Capturas

![Captura de EtherCalc](./doc/screenshots/screenshot.png)

## :red_circle: Características no deseables

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentaciones y recursos

- Sitio web oficial: <https://ethercalc.net/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/audreyt/ethercalc>
- Catálogo YunoHost: <https://apps.yunohost.org/app/ethercalc>
- Reportar un error: <https://github.com/YunoHost-Apps/ethercalc_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/ethercalc_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ethercalc_ynh/tree/testing --debug
o
sudo yunohost app upgrade ethercalc -u https://github.com/YunoHost-Apps/ethercalc_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
