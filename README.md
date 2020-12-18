Diaspora for YunoHost

[![Integration level](https://dash.yunohost.org/integration/diaspora.svg)](https://dash.yunohost.org/appci/app/diaspora) ![](https://ci-apps.yunohost.org/ci/badges/diaspora.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/diaspora.maintain.svg)[![Shipped version](https://img.shields.io/github/v/release/yunohost-apps/diaspora_ynh)](https://github.com/yunohost-apps/diaspora_ynh/releases)  
[![Install Diaspora with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=diaspora)

## Overview

> *This package allow you to install Diaspora quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

**Shipped version:** 0.7.13.0

## Notes

Before installing, you have to:

- get a dedicated domain (must install under web root like **https://diaspora.example.com/** not **https://example.com/diaspora/**)
- get a valid SSL certificate

Installation effects:

- Thank you for being patient as deployment time can take up to about 1 hour (raspberry pi).
- The installation directory can take up to 900MB and app start time can be take 5 minutes

## Links

 * Report a bug: https://github.com/YunoHost-Apps/diaspora_ynh/issues
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/diaspora_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/diaspora_ynh/tree/testing --debug
or
sudo yunohost app upgrade diaspora -u https://github.com/YunoHost-Apps/diaspora_ynh/tree/testing --debug
```
