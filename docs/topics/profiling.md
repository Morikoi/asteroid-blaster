# Profiling 

[Wikipedia](https://en.wikipedia.org/wiki/Profiling_(computer_programming)) says:

> Profiling is achieved by instrumenting either the program source code or its binary executable form using a tool called a profiler (or code profiler). Profilers may use a number of different techniques, such as event-based, statistical, instrumented, and simulation methods.

Continuous profiling can help you understand systems resource usage (CPU, memory, etc.), identify performance bottlenecks, locate memory leaks and analyse the call stack of your applications. You can also use it as a method to track performance changes over time.

## Open Telemetry Profiling Efforts
Within Open Telemetry, there is a working group who is working towards adding Profiling as a supported event type. For more details on the scope and vision check out the [OTel Profiling Vision OTEP](https://github.com/open-telemetry/oteps/blob/main/text/profiles/0212-profiling-vision.md) or drop in on the CNCF [#otel-profiling](https://cloud-native.slack.com/archives/C03J794L0BV) channel where most communication and coordination happens!

## Introductions

- [Current state of Continuous Profiling](https://o11y.engineering/the-state-of-continuous-profiling-b89cdbdd47f6), Dec 2021

## Tools 

### Datadog Continuous Profiler

- [Website](https://www.datadoghq.com/product/code-profiling/)
- [Documentation](https://docs.datadoghq.com/tracing/profiler/)

#### Facts

- You can [connect traces to profiling data](https://docs.datadoghq.com/tracing/profiler/#connect-traces-to-profiling-data). Learn more about [Tracing](../tr