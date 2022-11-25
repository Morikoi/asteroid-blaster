# Tracing

[Tracing](https://en.wikipedia.org/wiki/Tracing_(software)) defines a way of logging during program runtime. It enables developers to debug performance problems, with additional context and timing points provided. 

Distributed tracing workflows and OSS implementations have made tracing more popular in the recent years. ["What is distributed tracing and why does it matter?"](https://www.dynatrace.com/news/blog/what-is-distributed-tracing/) provides more history and insights.  

## History

- 2016: [OpenCensus](https://opencensus.io/) and [OpenTracing](https://opentracing.io/specification/) as specification and tools.
    - [Tracers](https://opentracing.io/docs/overview/tracers/): ZipKin, Jaeger, Datadog, Lightstep.
- 2019: OpenTelemetry [merges](https://