# Logs/Events

[Logging](https://en.wikipedia.org/wiki/Logging_(software)) defines creating a protocol of status information and events during runtime of services. Log and event management tools collect, store and provide query access to the data. 

Elastic, Splunk, etc. which provide an entire stack can be found in the [Platforms](../platforms) topic. 

## Introduction

## Tools

### Fluentd

> Fluentd is an open source data collector for unified logging layer. 

- [Website](https://www.fluentd.org/)
- [Documentation](https://docs.fluentd.org/)

#### Facts

- Fluentd is an open source data collector for unified logging layer.
- [CNCF project since 2016](https://www.cncf.io/projects/fluentd/)
- [Open Source](https://github.com/fluent/fluentd)

#### Hot Topics 

### Grafana Loki

> Loki is a log aggregation system designed to store and query logs from all your applications and infrastructure. 

- [Website](https://grafana.com/oss/loki/)
- [Documentation](https://grafana.com/docs/loki/latest/)

#### Facts

- Loki implements a similar query language like [PromQL](../metrics#prometheus), allowing for log and metrics aggregation in Grafana. 

#### Hot Topics 

### OpenSearch

- [Website](https://opensearch.org/)
- [Documentation](https://opensearch.org/docs/latest)

#### Facts

- [OpenSearch is an open-source fork of Elasticsearch and Kibana 7.10](https://aws.amazon.com/blogs/opensource/introducing-opensearch/)

#### Hot Topics 


## Use Cases 

- [Fast Logs Ingestion by Nicolas Fränkel](https://www.youtube.com/watch?v=DK9FM34YvXM) at OSDC 2019. Learn about structured logging and p