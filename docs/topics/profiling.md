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

- You can [connect traces to profiling data](https://docs.datadoghq.com/tracing/profiler/#connect-traces-to-profiling-data). Learn more about [Tracing](../tracing)

#### Hot Topics 

- [How we wrote a Python profiler](https://www.datadoghq.com/blog/engineering/how-we-wrote-a-python-profiler/)

### Google Cloud Profiler

- [Website](https://cloud.google.com/profiler)
- [Documentation](https://cloud.google.com/profiler/docs)

#### Facts

#### Hot Topics 

- [Tutorial: Optimizing a Go app](https://cloud.google.com/profiler/docs/quickstart-go-app)

### Parca

> From profiles to understanding. Open Source Infrastructure-wide continuous profiling 

- [Website](https://www.parca.dev/)
- [Documentation](https://www.parca.dev/docs/overview)

#### Facts

- Parca was open-source by [Polar Signals](https://www.polarsignals.com/) in 2021
- Parca's old name was `Conprof` which can be seen in [the KubeCon NA 2021 talk](https://www.youtube.com/watch?v=ficc6_6RYQk)

#### Hot Topics 

- [Feature requests for the Parca agent](https://github.com/parca-dev/parca-agent/issues)

### Pyroscope

- [Website](https://pyroscope