<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# ElasticSearch 7 pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/elasticsearch7.svg)](https://dash.yunohost.org/appci/app/elasticsearch7) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/elasticsearch7.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/elasticsearch7.maintain.svg)

[![Installer ElasticSearch 7 avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=elasticsearch7)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer ElasticSearch 7 rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Elasticsearch is the distributed, RESTful search and analytics engine at the heart of the [Elastic Stack](https://www.elastic.co/products). You can use Elasticsearch to store, search, and manage data for logs, metrics, search backend, application monitoring, Endpoint security.
To learn more about Elasticsearch’s features and capabilities, see the [product page](https://www.elastic.co/products/elasticsearch).


**Version incluse :** 7.17.8~ynh6

**Démo :** <https://www.elastic.co/demos>
## Avertissements / informations importantes

### Limitations
 - **Not totally free**: Licensed under SSPL, see for more information: <https://en.wikipedia.org/wiki/Server_Side_Public_License>
 - Currently the security is disabled
 - Therefore, the package is configured to remain not public for now (i.e. not accessible through the web, the apps depending on it should be installed on the same server)
 - Not scalable for now

## :red_circle: Anti-fonctionnalités

- **Application sous licence libre restreinte **: L'application packagée est sous une licence globalement libre, mais avec des clauses qui pourraient restreindre son utilisation.

## Documentations et ressources

- Site officiel de l’app : <https://elastic.co>
- Documentation officielle de l’admin : <https://www.elastic.co/guide/en/elasticsearch/reference/7.17/elasticsearch-intro.html>
- Dépôt de code officiel de l’app : <https://github.com/elastic/elasticsearch>
- YunoHost Store : <https://apps.yunohost.org/app/elasticsearch7>
- Signaler un bug : <https://github.com/YunoHost-Apps/elasticsearch7_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/elasticsearch7_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/elasticsearch7_ynh/tree/testing --debug
ou
sudo yunohost app upgrade elasticsearch7 -u https://github.com/YunoHost-Apps/elasticsearch7_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
