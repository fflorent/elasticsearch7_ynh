<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# ElasticSearch 7 para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/elasticsearch7.svg)](https://dash.yunohost.org/appci/app/elasticsearch7) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/elasticsearch7.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/elasticsearch7.maintain.svg)

[![Instalar ElasticSearch 7 con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=elasticsearch7)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar ElasticSearch 7 de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Elasticsearch is the distributed, RESTful search and analytics engine at the heart of the [Elastic Stack](https://www.elastic.co/products). You can use Elasticsearch to store, search, and manage data for logs, metrics, search backend, application monitoring, Endpoint security.
To learn more about Elasticsearch’s features and capabilities, see the [product page](https://www.elastic.co/products/elasticsearch).


**Versión proporcionada:** 7.17.8~ynh6

**Demo:** <https://www.elastic.co/demos>
## Avisos / información importante

### Limitations
 - **Not totally free**: Licensed under SSPL, see for more information: <https://en.wikipedia.org/wiki/Server_Side_Public_License>
 - Currently the security is disabled
 - Therefore, the package is configured to remain not public for now (i.e. not accessible through the web, the apps depending on it should be installed on the same server)
 - Not scalable for now

## :red_circle: Debes considerar

- **Not totally free upstream**: The packaged app is under an overall free license, but with clauses that may restrict its use.

## Documentación e recursos

- Web oficial da app: <https://elastic.co>
- Documentación oficial para admin: <https://www.elastic.co/guide/en/elasticsearch/reference/7.17/elasticsearch-intro.html>
- Repositorio de orixe do código: <https://github.com/elastic/elasticsearch>
- Tenda YunoHost: <https://apps.yunohost.org/app/elasticsearch7>
- Informar dun problema: <https://github.com/YunoHost-Apps/elasticsearch7_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/elasticsearch7_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/elasticsearch7_ynh/tree/testing --debug
ou
sudo yunohost app upgrade elasticsearch7 -u https://github.com/YunoHost-Apps/elasticsearch7_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
