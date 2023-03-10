# Platforms 

An Observability platform provides tools, methods and workflows to consume by users, and manage by platform teams (SaaS or self-managed).

## Overview

<!-- Keep it sorted alpha numeric. -->



### Aspecto 

- [Website](https://www.aspecto.io/)
- [Documentation](https://docs.asecpto.io/)

#### Facts

- Uses OpenTelemetry. 

#### Hot Topics 

- [Aspecto's blog](https://www.aspecto.io/blog/) We share everything we know about OpenTelemetry and o11y.
- [Trace based Testing](https://github.com/aspecto-io/malabi) A trace based testing open source by.
- [OpenTelemetry Bootcamp](https://www.aspecto.io/opentelemetry-bootcamp/) A free, vendor neutral bootcamp to learn about OpenTelemetry

### AWS

AWS provides multiple services on their platform: 

- [Amazon Managed Grafana](https://aws.amazon.com/grafana/)
- [Amazon Managed Service for Prometheus](https://aws.amazon.com/prometheus/)
- [Amazon OpenSearch Service](https://aws.amazon.com/opensearch-service/)
- [AWS Distro for OpenTelemetry](https://aws.amazon.com/otel/?otel-blogs.sort-by=item.additionalFields.createdDate&otel-blogs.sort-order=desc)

#### Facts

- Managed Service for Prometheus and Grafana was [launched in Dec 2020](https://twitter.com/rakyll/status/1338902037644206081)

#### Hot Topics 

- [AWS Observability Recipes](https://aws-observability.github.io/aws-o11y-recipes/)
- [Build an observability solution using managed AWS services and the OpenTelemetry standard](https://aws.amazon.com/blogs/mt/build-an-observability-solution-using-managed-aws-services-and-the-opentelemetry-standard/)

### Datadog 

- [Website](https://www.datadoghq.com/)
- [Documentation](https://docs.datadoghq.com/)

#### Facts

- SaaS, free and pair tier.
- [Agent is OSS](https://github.com/DataDog/datadog-agent)

#### Hot Topics 

- [CI Visibility](https://www.datadoghq.com/product/ci-cd-monitoring/)

### Dynatrace 

- [Website](https://www.dynatrace.com/)
- [Documentation](https://www.dynatrace.com/support/help)

#### Facts

- [Dynatrace created Keptn for CI/CD quality gates and SLOs](https://everyonecancontribute.com/post/2020-11-11-cafe-8-keptn/), donated to CNCF. 

#### Hot Topics 

- [Open Observability: Distributed Tracing and Observability](https://www.dynatrace.com/news/blog/open-observability-part-1-distributed-tracing-and-observability/)

### Elastic

- [Website](https://www.elastic.co/)
- [Documentation](https://www.elastic.co/guide/index.html)

#### Facts

- The `ELK stack` refers to Elasticsearch, Logstash, Kibana as tools. 
- Beats and agent collectors inspired the name change to `Elastic Stack`. 
- Elastic [changed the Apache 2.0-licensed source code of Elasticsearch and Kibana](https://www.elastic.co/pricing/faq/licensing) to proprietary Elastic license or SSPL in 2021. 
- Elastic APM is included in [Elastic Observability](https://www.elastic.co/observability). 

#### Hot Topics 

- [Real User Monitoring (RUM)](https://www.elastic.co/guide/en/apm/get-started/current/rum.html)

### Google Cloud Operations

- [Website](https://cloud.google.com/products/operations)
- [Documentation](https://cloud.google.com/products/operations#section-4) 

#### Facts

- [Supports OpenTelemetry](https://cloud.google.com/learn/what-is-opentelemetry)

#### Hot Topics 

- [Google donated Sqlcomment to OpenTelemetry](https://devops.com/google-donates-sqlcommenter-to-opentelemetry-project/) in Sep 2021. This helps to correlate application and database telemetry.

### Grafana 

- [Website](https://grafana.com/)
- [Documentation](https://grafana.com/docs/)

#### Facts

- Grafana evolved from a metrics dashboard to a platform with many data sources, plugins and dashboards
- The [Grafana agent code](https://twitter.com/gehrcke/status/1455509846049054722?s=20) was contributed to create the Prometheus agent. Learn more about [Metrics](../metrics).
- [Grafana is a fork of Kibana 3](https://grafana.com/blog/2019/09/03/the-mostly-complete-history-of-grafana-ux/)
- [Grafana Labs changed the license to AGPLv3 for Grafana, Loki, and Tempo](https://www.infoq.com/news/2021/04/grafana-licence-agpl/) in April 2021

#### Hot Topics 

- [A beginner's guide to network monitoring with Grafana and Prometheus](https://grafana.com/blog/2022/01/19/a-beginners-guide-to-network-monitoring-with-grafana-and-prometheus/)

### Honeycomb

- [Website](https://www.honeycomb.io/)
- [Documentation](https://docs.honeycomb.io/)

#### Facts

- SaaS, free and paid tier. 
- Honeycomb created so-called [Beelines](https://docs.honeycomb.io/getting-data-in/go/), small agents to send instrumentation data to the SaaS platform. 
- Honeycomb [supports OpenTelemetry](https://docs.honeycomb.io/getting-data-in/opentelemetry/).

#### Hot Topics 

- [Honeycomb's blog](https://www.honeycomb.io/blog/) is a wealth of knowledge and thought leadership for o11y.

### NewRelic 

- [Website](https://newrelic.com/)
- [Documentation](https://docs.newrelic.com/)

#### Facts

- SaaS, free and paid tier. 
- NewRelic acquired [Pixie for Kubernetes Observability](https://newrelic.com/platform/kubernetes-pixie).

#### Hot Topics 

- Integrates with [OpenTelemetry](https://docs.newrelic.com/docs/more-integrations/open-source-telemetry-integrations/opentelemetry/introduction-opentelemetry-new-relic/).

### Nobl9

- [Website](https://www.nobl9.com/)

#### Facts

- Service Level Objective (SLO) platform. SaaS, paid tier. 
- Initiators of [SLOConf](https://www.sloconf.com/) and [OpenSLO](../collections-specs#openslo). 

#### Hot Topics 

- [Integration with Prometheus](https://www.nobl9.com/platform/integrations)

### Opstrace 

- [Website](https://opstrace.com/)
- [Documentation](https://opstrace.com/docs)

#### Facts

- Observability Distribution, secure and multi-tenants 
- [Acquired by GitLab](https://opstrace.com/blog/gitlab) in December 2021.
- First demo in the [25. #EveryoneCanContribute cafe](https://everyonecancontribute.com/post/2021-04-14-cafe-25-opstrace-observability/) in April 2021.

#### Hot Topics 

- [Integration milestones](https://gitlab.com/gitlab-org/opstrace/opstrace/-/milestones)

### Splunk

- [Website](https://www.splunk.com/)
- [Documentation](https://docs.splunk.com/Documentation)

#### Facts

- Splunk was founded in 2003 and dominated the log collection market for many years. 

#### Hot Topics 

- [Splunk Observability](https://www.splunk.com/en_us/devops.html) 
