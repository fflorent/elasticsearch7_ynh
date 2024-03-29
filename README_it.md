<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# ElasticSearch 7 per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/elasticsearch7.svg)](https://dash.yunohost.org/appci/app/elasticsearch7) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/elasticsearch7.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/elasticsearch7.maintain.svg)

[![Installa ElasticSearch 7 con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=elasticsearch7)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare ElasticSearch 7 su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Elasticsearch is the distributed, RESTful search and analytics engine at the heart of the [Elastic Stack](https://www.elastic.co/products). You can use Elasticsearch to store, search, and manage data for logs, metrics, search backend, application monitoring, Endpoint security.
To learn more about Elasticsearch’s features and capabilities, see the [product page](https://www.elastic.co/products/elasticsearch).


**Versione pubblicata:** 7.17.8~ynh6

**Prova:** <https://www.elastic.co/demos>
## Attenzione/informazioni importanti

### Limitations
 - **Not totally free**: Licensed under SSPL, see for more information: <https://en.wikipedia.org/wiki/Server_Side_Public_License>
 - Currently the security is disabled
 - Therefore, the package is configured to remain not public for now (i.e. not accessible through the web, the apps depending on it should be installed on the same server)
 - Not scalable for now

## :red_circle: Anti-funzionalità

- **Applicazione con licenza parzialmente libera**: Quest’applicazione è protetta da licenza generalmente libera, ma con delle clausole che potrebbero limitare il suo utilizzo.

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://elastic.co>
- Documentazione ufficiale per gli amministratori: <https://www.elastic.co/guide/en/elasticsearch/reference/7.17/elasticsearch-intro.html>
- Repository upstream del codice dell’app: <https://github.com/elastic/elasticsearch>
- Store di YunoHost: <https://apps.yunohost.org/app/elasticsearch7>
- Segnala un problema: <https://github.com/YunoHost-Apps/elasticsearch7_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/elasticsearch7_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/elasticsearch7_ynh/tree/testing --debug
o
sudo yunohost app upgrade elasticsearch7 -u https://github.com/YunoHost-Apps/elasticsearch7_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
