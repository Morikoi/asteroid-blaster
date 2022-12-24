# Tracing

[Tracing](https://en.wikipedia.org/wiki/Tracing_(software)) defines a way of logging during program runtime. It enables developers to debug performance problems, with additional context and timing points provided. 

Distributed tracing workflows and OSS implementations have made tracing more popular in the recent years. ["What is distributed tracing and why does it matter?"](https://www.dynatrace.com/news/blog/what-is-distributed-tracing/) provides more history and insights.  

## History

- 2016: [OpenCensus](https://opencensus.io/) and [OpenTracing](https://opentracing.io/specification/) as specification and tools.
    - [Tracers](https://opentracing.io/docs/overview/tracers/): ZipKin, Jaeger, Datadog, Lightstep.
- 2019: OpenTelemetry [merges](https://opensource.googleblog.com/2019/05/opentelemetry-merger-of-opencensus-and.html) OpenTracing and OpenCensus
    - [CNCF TAG Observability](https://github.com/cncf/tag-observability): [OpenTelemetry project](https://www.cncf.io/blog/2019/05/21/a-brief-history-of-opentelemetry-so-far/) starts with tracing.
- 2020: Grafana announces Tempo.
- 2021: OpenTelemetry adds metrics and logs [specifications](https://github.com/open-telemetry/opentelemetry-specification/tree/main/specification).
- 2021: OpenTelemetry becomes [CNCF Incubating project](https://www.cncf.io/blog/2021/08/26/opentelemetry-becomes-a-cncf-incubating-project/). 
- 2022: [OpenTracing deprecation](https://github.com/opentracing/specification/issues/163).

Learn more about [OpenTelemetry in the Collections/Spec topic](../collections-specs#opentelemetry).

## Tools

### Jaeger 

- [Website](https://www.jaegertracing.io/)

#### Facts

- Open source, end-to-end distributed tracing.
- [Jaeger exposes metrics](https://www.jaegertracing.io/docs/1.30/monitoring/) for [Prometheus](../metrics#prometheus) monitoring.

#### Hot Topics 

### Grafana Tempo 

- [Website](https: