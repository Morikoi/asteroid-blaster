
# Learning Resources

<!-- 
[![ALT](https://img.youtube.com/vi/XXX/0.jpg)](https://www.youtube.com/watch?v=xxx)
-->

## Articles

- [Observability with OpenTelemetry](https://trstringer.com/otel-part1-intro/) is a great learning series by Thomas Stringer in 5 parts, covering [Introduction](https://trstringer.com/otel-part1-intro/), [Instrumentation](https://trstringer.com/otel-part2-instrumentation/), [Exporting](https://trstringer.com/otel-part3-export/), [Collector](https://trstringer.com/otel-part4-collector/), [Propagation](https://trstringer.com/otel-part5-propagation/), [Ecosystem](https://trstringer.com/otel-part6-ecosystem/).
- [Prometheus vs. OpenTelemetry Metrics: A Complete Guide](https://www.timescale.com/blog/prometheus-vs-opentelemetry-metrics-a-complete-guide/)

## Newsletters 

Make sure to subscribe and also learn more in their online archive. 

- [o11y.news](https://o11y.news) by [Michael Hausenblas](https://twitter.com/mhausenblas)
- [monitoring weekly](https://monitoring.love/) by [Jason Dixon](https://twitter.com/obfuscurity)
- [opsindev.news](https://opsindev.news/) by [Michael Friedrich](https://twitter.com/dnsmichi)

## Workshops 

### Kubernetes Observability workshop for Kube Simplify

Michael Friedrich provides a 3.5 hours live workshop on Kubernetes Observability for the [Kube Simplify workshop series](https://kubesimplify.github.io/live-workshops/) as a free learning resource. After an introduction, the workshop starts with an overview of monitoring, metrics with Prometheus, and how to build and use dashboards in Kubernetes. Alerts, incidents and SLOs are practiced by example, building the bridge into more Observability data with tracing, logs and more event types. Chaos engineering is practiced with Chaos Mesh to trigger alerts when DNS errors force an app to leak memory. This allows users to practice the [KubeCon EU 2022 demo](https://youtu.be/BkREMg8adaI) themselves. Scaling, long term storage, security workflows as well as new innovative ideas with OpenTelemetry and eBPF are discussed too. The workshop includes exercises and solutions ready for production environments afterwards. 

Resources:

- [Slides with exercises](https://docs.google.com/presentation/d/1uuYIPwQjckNiPPJQcN8tauZ8KSIdHASbyoAxJ0fc6uQ/edit?usp=sharing)
- [Project with solutions](https://gitlab.com/everyonecancontribute/workshops/kube-simplify/k8s-o11y-2022)

Recording:

[![Kube Simplify: Kubernetes Observability workshop](https://img.youtube.com/vi/sMEEVbZ4NFM/0.jpg)](https://www.youtube.com/watch?v=sMEEVbZ4NFM)

Table of Content, [added to the recording](https://www.youtube.com/watch?v=sMEEVbZ4NFM&lc=Ugzu0fRX7RC86e18iMh4AaABAg): 

```
1:38 Introduction with Saiyam and Michael 
8:10 Workshop Start 
8:58 What to expect 
10:05 Workshop requirements 
12:22 Tips 
15:06 Monitoring, quo vadis - in a nutshell, black-box, metrics/trends, microservices, whitebox
23:00 Kubernetes - learn what to monitor 
29:45 Metrics with Prometheus - Architecture, PromQL, UI, 
39:15 Prometheus Operator - install Prometheus in Kubernetes 
52:22 Kubernetes Metrics 