
# Metrics 

Metrics are quantitative measures. In the era of Monitoring and Observability, they became a standard term for collecting application performance data. [OpenMetrics](../collections-specs#openmetrics) defines a standard for metrics and Observability. Metrics are often defined as key-value pairs stored in a [time series database (TSDB)](https://en.wikipedia.org/wiki/Time_series_database). 

Datadog, Opstrace, etc. which provide an entire stack can be found in the [Platforms](../platforms) topic. 

## Tools

### Prometheus 

- [Website](https://prometheus.io/)
- [Documentation](https://prometheus.io/docs/introduction/overview/)

#### Facts

- Started in 2012
- [Open Source](https://github.com/prometheus)
- [CNCF graduated project in 2018](https://www.cncf.io/announcements/2018/08/09/prometheus-graduates/)

#### Hot Topics 

- [PromQL](https://prometheus.io/docs/prometheus/latest/querying/basics/) query language.
- [Metric Types](https://prometheus.io/docs/concepts/metric_types/)
- [Exporters](https://prometheus.io/docs/instrumenting/exporters/) where Prometheus can scrape metrics from.
- [Instrumentation](https://prometheus.io/docs/instrumenting/clientlibs/) for your app source, exposing `/metrics`. 

### Cortex 

- [Website](https://cortexmetrics.io/)
- [Documentation](https://cortexmetrics.io/docs/)

#### Facts

- Cortex provides horizontally scalable, highly available, multi-tenant, long term storage for Prometheus.

#### Hot Topics 

[Difference between Cortex and Thanos](https://thenewstack.io/thanos-takes-scalable-highly-available-prometheus-monitoring-to-cncf-incubation/):

> The real difference between the projects, said Plotka, comes in some initial design approaches, with Cortex using a push-based system, while Thanos is pull-based. Thanos also relies on object storage, which Plotka points out is very affordable, while Cortex uses NoSQL as well as object storage. The final initial difference is that Thanos used time-series database format, whereas Cortex used a custom indexed time-series database.

### Thanos

- [Website](https://thanos.io/)
- [Documentation](https://thanos.io/tip/thanos/getting-started.md/)

#### Facts

- Open source, highly available Prometheus setup with long term storage capabilities.

#### Hot Topics 

[Difference between Cortex and Thanos](https://thenewstack.io/thanos-takes-scalable-highly-available-prometheus-monitoring-to-cncf-incubation/):

> The real difference between the projects, said Plotka, comes in some initial design approaches, with Cortex using a push-based system, while Thanos is pull-based. Thanos also relies on object storage, which Plotka points out is very affordable, while Cortex uses NoSQL as well as object storage. The final initial difference is that Thanos used time-series database format, whereas Cortex used a custom indexed time-series database.


## Use Cases 

- [Prometheus Deep Dive - Goutham Veeramachaneni, Grafana Labs & Bartłomiej Płotka, Red Hat](https://www.youtube.com/watch?v=Xx16tAoqw70) at KubeCon EU 2020
- [How We are Dealing with Metrics at Scale on GitLab.com - Andrew Newdigate, GitLab](https://www.youtube.com/watch?v=6sfr2IGJQXk) at KubeCon EU 2021