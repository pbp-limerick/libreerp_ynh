<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# LibreERP YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/libreerp.svg)](https://dash.yunohost.org/appci/app/libreerp) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/libreerp.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/libreerp.maintain.svg)

[![Instalatu LibreERP YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=libreerp)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek LibreERP YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

LibreERP is a suite of web based open source business apps. LibreERP is a fork of Odoo Community Edition.

The main LibreERP Apps include an Open Source CRM, Website Builder, eCommerce, Project Management, Billing &amp; Accounting, Point of Sale, Human Resources, Marketing, Manufacturing, Purchase Management, ...

LibreERP Apps can be used as stand-alone applications, but they also integrate seamlessly so you get a full-featured Open Source ERP when you install several Apps.


**Paketatutako bertsioa:** 16.0~ynh2

**Demoa:** <https://www.odoo.com/trial>
## Ezespena / informazio garrantzitsua

**WARNING**: LibreERP is a complex app. **DO NOT USE THIS PACKAGE** to run your business unless you know what you are doing!!! If you don't, you should consider to ask for help from a professionnal!

**IMPORTANT:** This app MUST be installed on a domain's root!
https://erp.example.com/ will work
https://example.com/erp/ will NOT work

To connect on your LibreERP
-----------
- Go on https://YOURDOMAIN/web
- Login as "admin" with the master password you provided during installation

About licences
-----------
LibreERP 8.0 is under AGPL-3.0
Next version are under LGPL-3.0
LibreERP is forked from Odoo Community Edition. The name is change due to Odoo trademark policy.

## :red_circle: Ezaugarri zalantzagarriak

- **Ordainpeko edukia**: Ordainpeko zerbitzu bat sustatzen du edo bere mende dago, osorik edo neurri batean.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://odoo.com>
- Erabiltzaileen dokumentazio ofiziala: <https://www.odoo.com/documentation/16.0/applications.html>
- Administratzaileen dokumentazio ofiziala: <https://www.odoo.com/documentation/16.0/administration.html>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/odoo/odoo>
- YunoHost Denda: <https://apps.yunohost.org/app/libreerp>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/libreerp_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/libreerp_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/libreerp_ynh/tree/testing --debug
edo
sudo yunohost app upgrade libreerp -u https://github.com/YunoHost-Apps/libreerp_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
