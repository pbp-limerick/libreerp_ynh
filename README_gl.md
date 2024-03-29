<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# LibreERP para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/libreerp.svg)](https://dash.yunohost.org/appci/app/libreerp) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/libreerp.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/libreerp.maintain.svg)

[![Instalar LibreERP con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=libreerp)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar LibreERP de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

LibreERP is a suite of web based open source business apps. LibreERP is a fork of Odoo Community Edition.

The main LibreERP Apps include an Open Source CRM, Website Builder, eCommerce, Project Management, Billing &amp; Accounting, Point of Sale, Human Resources, Marketing, Manufacturing, Purchase Management, ...

LibreERP Apps can be used as stand-alone applications, but they also integrate seamlessly so you get a full-featured Open Source ERP when you install several Apps.


**Versión proporcionada:** 16.0~ynh2

**Demo:** <https://www.odoo.com/trial>
## Avisos / información importante

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

## :red_circle: Caraterísticas cuestionables

- **Paid content**: Promotes or depends, entirely or partially, on a paid service.

## Documentación e recursos

- Web oficial da app: <https://odoo.com>
- Documentación oficial para usuarias: <https://www.odoo.com/documentation/16.0/applications.html>
- Documentación oficial para admin: <https://www.odoo.com/documentation/16.0/administration.html>
- Repositorio de orixe do código: <https://github.com/odoo/odoo>
- Tenda YunoHost: <https://apps.yunohost.org/app/libreerp>
- Informar dun problema: <https://github.com/YunoHost-Apps/libreerp_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/libreerp_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/libreerp_ynh/tree/testing --debug
ou
sudo yunohost app upgrade libreerp -u https://github.com/YunoHost-Apps/libreerp_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
