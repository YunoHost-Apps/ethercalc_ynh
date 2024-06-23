<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# EtherCalc YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/ethercalc.svg)](https://dash.yunohost.org/appci/app/ethercalc) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/ethercalc.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/ethercalc.maintain.svg)

[![Instalatu EtherCalc YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ethercalc)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek EtherCalc YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

EtherCalc is a collaborative spreadsheet that can be edited in real time. Each spreadsheet has its own URL. It has the basic functionalities: formatting, mathematical functions, graphics, adding comments, version history, export in HTML or in CSV. EtherCalc is a decentralized software: different instances allow the use of the service, they are made available by several organizations (for example the eponymous site or the FramaCalc service). This makes it possible to avoid concentrating all the data in the hands of the same actor. Instances can be personalized (limitation of the duration of hosting of the spreadsheet, modification of the design, etc.).

**Paketatutako bertsioa:** 20240101~ynh1

**Demoa:** <https://ethercalc.net/>

## Pantaila-argazkiak

![EtherCalc(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizko garapena utzita**: Software honek ez du arduradunik. Denborak aurrera egin ahala funtzionatzeari utziko dio, konpondu gabeko segurtasun arazoak izango ditu, etab.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://ethercalc.net/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/audreyt/ethercalc>
- YunoHost Denda: <https://apps.yunohost.org/app/ethercalc>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/ethercalc_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/ethercalc_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ethercalc_ynh/tree/testing --debug
edo
sudo yunohost app upgrade ethercalc -u https://github.com/YunoHost-Apps/ethercalc_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
