<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# ElasticSearch 7 for YunoHost

[![Integration level](https://dash.yunohost.org/integration/elasticsearch7.svg)](https://dash.yunohost.org/appci/app/elasticsearch7) ![Working status](https://ci-apps.yunohost.org/ci/badges/elasticsearch7.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/elasticsearch7.maintain.svg)

[![Install ElasticSearch 7 with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=elasticsearch7)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install ElasticSearch 7 quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Elasticsearch is the distributed, RESTful search and analytics engine at the heart of the [Elastic Stack](https://www.elastic.co/products). You can use Elasticsearch to store, search, and manage data for logs, metrics, search backend, application monitoring, Endpoint security.
To learn more about Elasticsearch’s features and capabilities, see the [product page](https://www.elastic.co/products/elasticsearch).


**Shipped version:** 7.17.8~ynh6

**Demo:** https://www.elastic.co/demos
## Disclaimers / important information

### Limitations
 - **Not totally free**: Licensed under SSPL, see for more information: <https://en.wikipedia.org/wiki/Server_Side_Public_License>
 - Currently the security is disabled
 - Therefore, the package is configured to remain not public for now (i.e. not accessible through the web, the apps depending on it should be installed on the same server)
 - Not scalable for now

## :red_circle: Antifeatures

- **Not totally free upstream**: The packaged app is under an overall free licence, but with clauses that restrict its use.

## Documentation and resources

* Official app website: <https://elastic.co>
* Official admin documentation: <https://www.elastic.co/guide/en/elasticsearch/reference/7.17/elasticsearch-intro.html>
* Upstream app code repository: <https://github.com/elastic/elasticsearch>
* YunoHost documentation for this app: <https://yunohost.org/app_elasticsearch7>
* Report a bug: <https://github.com/YunoHost-Apps/elasticsearch7_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/elasticsearch7_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/elasticsearch7_ynh/tree/testing --debug
or
sudo yunohost app upgrade elasticsearch7 -u https://github.com/YunoHost-Apps/elasticsearch7_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
