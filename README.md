<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# httpsh on ttyd for YunoHost

[![Integration level](https://dash.yunohost.org/integration/httpsh.svg)](https://dash.yunohost.org/appci/app/httpsh) ![Working status](https://ci-apps.yunohost.org/ci/badges/httpsh.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/httpsh.maintain.svg)

[![Install httpsh on ttyd with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=httpsh)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install httpsh on ttyd quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

This package is based on two projects:

* [ttyd](https://tsl0922.github.io/ttyd) is a TTY (terminal) web server
* [httpsh](https://github.com/leshniak/httpsh) is a script that is called by ttyd


**Shipped version:** 1.7.3~ynh1

## Screenshots

![Screenshot of httpsh on ttyd](./doc/screenshots/example.jpg)

## Documentation and resources

* Official admin documentation: <https://github.com/tsl0922/ttyd/wiki/Example-Usage>
* Upstream app code repository: <https://github.com/leshniak/httpsh>
* YunoHost documentation for this app: <https://yunohost.org/app_httpsh>
* Report a bug: <https://github.com/YunoHost-Apps/httpsh_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing --debug
or
sudo yunohost app upgrade httpsh -u https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
