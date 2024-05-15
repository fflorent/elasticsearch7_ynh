<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 ElasticSearch 7

[![集成程度](https://dash.yunohost.org/integration/elasticsearch7.svg)](https://dash.yunohost.org/appci/app/elasticsearch7) ![工作状态](https://ci-apps.yunohost.org/ci/badges/elasticsearch7.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/elasticsearch7.maintain.svg)

[![使用 YunoHost 安装 ElasticSearch 7](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=elasticsearch7)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 ElasticSearch 7。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Elasticsearch is the distributed, RESTful search and analytics engine at the heart of the [Elastic Stack](https://www.elastic.co/products). You can use Elasticsearch to store, search, and manage data for logs, metrics, search backend, application monitoring, Endpoint security.
To learn more about Elasticsearch’s features and capabilities, see the [product page](https://www.elastic.co/products/elasticsearch).


**分发版本：** 7.17.8~ynh6

**演示：** <https://www.elastic.co/demos>
## 免责声明 / 重要信息

### Limitations
 - **Not totally free**: Licensed under SSPL, see for more information: <https://en.wikipedia.org/wiki/Server_Side_Public_License>
 - Currently the security is disabled
 - Therefore, the package is configured to remain not public for now (i.e. not accessible through the web, the apps depending on it should be installed on the same server)
 - Not scalable for now

## :red_circle: 负面特征

- **Not totally free upstream**: The packaged app is under an overall free license, but with clauses that may restrict its use.

## 文档与资源

- 官方应用网站： <https://elastic.co>
- 官方管理文档： <https://www.elastic.co/guide/en/elasticsearch/reference/7.17/elasticsearch-intro.html>
- 上游应用代码库： <https://github.com/elastic/elasticsearch>
- YunoHost 商店： <https://apps.yunohost.org/app/elasticsearch7>
- 报告 bug： <https://github.com/YunoHost-Apps/elasticsearch7_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/elasticsearch7_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/elasticsearch7_ynh/tree/testing --debug
或
sudo yunohost app upgrade elasticsearch7 -u https://github.com/YunoHost-Apps/elasticsearch7_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
