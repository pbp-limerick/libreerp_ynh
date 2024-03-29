<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# LibreERP per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/libreerp.svg)](https://dash.yunohost.org/appci/app/libreerp) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/libreerp.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/libreerp.maintain.svg)

[![Installa LibreERP con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=libreerp)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare LibreERP su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

LibreERP is a suite of web based open source business apps. LibreERP is a fork of Odoo Community Edition.

The main LibreERP Apps include an Open Source CRM, Website Builder, eCommerce, Project Management, Billing &amp; Accounting, Point of Sale, Human Resources, Marketing, Manufacturing, Purchase Management, ...

LibreERP Apps can be used as stand-alone applications, but they also integrate seamlessly so you get a full-featured Open Source ERP when you install several Apps.


**Versione pubblicata:** 16.0~ynh2

**Prova:** <https://www.odoo.com/trial>
## Attenzione/informazioni importanti

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

## :red_circle: Anti-funzionalità

- **Contenuti a pagamento**: Promuove o dipende, interamente o parzialmente, da un servizio a pagamento.

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://odoo.com>
- Documentazione ufficiale per gli utenti: <https://www.odoo.com/documentation/16.0/applications.html>
- Documentazione ufficiale per gli amministratori: <https://www.odoo.com/documentation/16.0/administration.html>
- Repository upstream del codice dell’app: <https://github.com/odoo/odoo>
- Store di YunoHost: <https://apps.yunohost.org/app/libreerp>
- Segnala un problema: <https://github.com/YunoHost-Apps/libreerp_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/libreerp_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/libreerp_ynh/tree/testing --debug
o
sudo yunohost app upgrade libreerp -u https://github.com/YunoHost-Apps/libreerp_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
