---
layout：default title：OpenSearch documentation nav_order：1 has_children：true 永久链接：/
---

{% include banner.html %}

# 开始

- [关于 OpenSearch]({{site.url}}{{site.baseurl}}/opensearch/)
- [Quickstart]({{site.url}}{{site.baseurl}}/quickstart/)
- [安装 OpenSearch]({{site.url}}{{site.baseurl}}/install-and-configure/install-opensearch/index/)
- [安装 OpenSearch 控制面板]({{site.url}}{{site.baseurl}}/install-and-configure/install-dashboards/index/)
- [查看常见问题](https://opensearch.org/faq)

## 为什么要使用 OpenSearch？

借助 OpenSearch，你可以执行以下使用案例：

<table style="table-layout: auto ; width: 100%;">
<tbody>
<tr style="text-align: center; vertical-align:center;">
<td><img src="{{site.url}}{{site.baseurl}}/images/1_search.png" class="no-border" alt="Fast, scalable full-text search" height="100"/></td>
<td><img src="{{site.url}}{{site.baseurl}}/images/2_monitoring.png" class="no-border" alt="Application and infrastructure monitoring" height="100"/></td>
<td><img src="{{site.url}}{{site.baseurl}}/images/3_security.png" class="no-border" alt="Security and event information management" height="100"/></td>
<td><img src="{{site.url}}{{site.baseurl}}/images/4_tracking.png" class="no-border" alt="Operational health tracking" height="100"/></td>
</tr>
<tr style="text-align: left; vertical-align:top; font-weight: bold; color: rgb(0,59,92)">
<td>Fast, Scalable Full-text Search</td>
<td>Application and Infrastructure Monitoring</td>
<td>Security and Event Information Management</td>
<td>Operational Health Tracking</td>
</tr>
<tr style="text-align: left; vertical-align:top;">
<td>Help users find the right information within your application, website, or data lake catalog. </td>
<td>Easily store and analyze log data, and set automated alerts for underperformance.</td>
<td>Centralize logs to enable real-time security monitoring and forensic analysis.</td>
<td>Use observability logs, metrics, and traces to monitor your applications and business in real time.</td>
</tr>
</tbody>
</table>

**附加功能和插件：**

OpenSearch 具有多种功能和插件，可帮助索引、保护、监控和分析你的数据。大多数 OpenSearch 插件都有相应的 OpenSearch 控制面板插件，这些插件提供方便、统一的用户界面。
- [异常检测]({{site.url}}{{site.baseurl}}/monitoring-plugins/ad/) - 识别非典型数据并接收自动通知
- [KNN]({{site.url}}{{site.baseurl}}/search-plugins/knn/) - 在矢量数据中找到“最近邻”
- [性能分析器]({{site.url}}{{site.baseurl}}/monitoring-plugins/pa/) - 监控和优化集群
- [SQL]({{site.url}}{{site.baseurl}}/search-plugins/sql/index/) - 使用 SQL 或管道处理语言查询数据
- [索引状态管理]({{site.url}}{{site.baseurl}}/im-plugin/) - 自动执行索引操作
- [ML Commons 插件]({{site.url}}{{site.baseurl}}/ml-commons-plugin/index/) - 训练和执行机器学习模型
- [异步搜索]({{site.url}}{{site.baseurl}}/search-plugins/async/) - 在后台运行搜索请求
- [跨集群复制]({{site.url}}{{site.baseurl}}/replication-plugin/index/) - 跨多个 OpenSearch 集群复制数据


## 安全前行之路
OpenSearch 包含一个演示配置，以便你可以快速启动和运行，但在生产环境中使用 OpenSearch 之前，你必须[手动配置安全插件]({{site.url}}{{site.baseurl}}/security/configuration/index/)使用自己的证书、身份验证方法、用户和密码。

## 寻找 Javadoc？

请参见[opensearch.org/javadocs/](https://opensearch.org/javadocs/)。

## 参与其中

[OpenSearch](https://opensearch.org)受 Amazon Web Services 支持。所有组件均可在 on [GitHub](https://github.com/opensearch-project/)下[Apache 许可证，版本 2.0](https://www.apache.org/licenses/LICENSE-2.0.html)使用。该项目欢迎 GitHub 问题、错误修复、功能、插件、文档---任何东西。要参与其中，请参阅[贡献](https://opensearch.org/source.html) OpenSearch 网站。

---

<small>OpenSearch 包含来自 Elasticsearch B.V. 的某些 Apache 许可的 Elasticsearch 代码和其他源代码。Elasticsearch B.V. 不是其他源代码的来源。ELASTICSEARCH 是 Elasticsearch B.V. 的注册商标。</small>