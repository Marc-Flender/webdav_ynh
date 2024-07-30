<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# My Webdav for YunoHost

[![Integration level](https://dash.yunohost.org/integration/my_webdav.svg)](https://ci-apps.yunohost.org/ci/apps/my_webdav/) ![Working status](https://ci-apps.yunohost.org/ci/badges/my_webdav.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/my_webdav.maintain.svg)

[![Install My Webdav with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=my_webdav)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install My Webdav quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

This application gives access to your Yunohost server with Webdav protocol

### Features

* authentication with Yunohost credentials
	* User
	* password
* Access to Webdav directory thanks to  URL: https://domain-name/my_webdav
* NB1: **do not add user's name at the end of URL**
* NB2: the file myfile, in  **https://domain-name/my_webdav/myfile**
will be stored, on the server, in the path of the connected user: **/home/yunoshot.multimedia/user**



**Shipped version:** 1.2~ynh1
## Documentation and resources

- Upstream app code repository: <https://github.com/YunoHost-Apps/my_webdav_ynh>
- YunoHost Store: <https://apps.yunohost.org/app/my_webdav>
- Report a bug: <https://github.com/YunoHost-Apps/my_webdav_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/my_webdav_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/my_webdav_ynh/tree/testing --debug
or
sudo yunohost app upgrade my_webdav -u https://github.com/YunoHost-Apps/my_webdav_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
