<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Faircamp for YunoHost

[![Integration level](https://apps.yunohost.org/badge/integration/faircamp)](https://ci-apps.yunohost.org/ci/apps/faircamp/)
![Working status](https://apps.yunohost.org/badge/state/faircamp)
![Maintenance status](https://apps.yunohost.org/badge/maintained/faircamp)

[![Install Faircamp with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=faircamp)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Faircamp quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Faircamp is a [Static Site Generator](https://en.wikipedia.org/wiki/Static_site_generator) dedicated to music producers.

With this package, Faircamp will automatically regenerate ([using Systemd Path Units](https://www.putorius.net/systemd-path-units.html)) your website if any change is made to your sources.

Alternatively to this package, you can [install Faircamp on your computer](https://simonrepp.com/faircamp/manual/installation.html) and use its rsync feature (ith the `--deploy` or `--deploy-destination` options) to send the builded website to a [My Webapp](https://apps.yunohost.org/app/my_webapp) folder on your YunoHost server.


**Shipped version:** 0.23.0~ynh1

## Screenshots

![Screenshot of Faircamp](./doc/screenshots/faircamp-screenshot.png)

## Documentation and resources

- Official app website: <https://simonrepp.com/faircamp/>
- Official admin documentation: <https://simonrepp.com/faircamp/manual/>
- Upstream app code repository: <https://codeberg.org/simonrepp/faircamp>
- YunoHost Store: <https://apps.yunohost.org/app/faircamp>
- Report a bug: <https://github.com/YunoHost-Apps/faircamp_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing --debug
or
sudo yunohost app upgrade faircamp -u https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
