
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
54:45 Prometheus Metrics in Grafana - Dashboards inspection, deployed by Prometheus Operator 
1:02:56 Workshop dashboards in Grafana - first panel and Kubernetes dashboard, container metrics, kube-state-metrics, 
1:21:34 ServiceMonitor CRD for /metrics endpoints auto discovery with Prometheus 
1:37:56 Monitoring 2.0 - Prometheus client libraries & instrumentation, 
1:45:43 Alerts and SLOs - Prometheus Operator CRDs, Alert Manager, podtato-head
1:55:53 Trigger alerts for podtato-head deployment - blackbox probe, dashboards, alert rules, 
2:14:45 Service Level Objectives & Ops Confidence  - Golden Signals, SLOs as code, 
2:19:15 Customize kube-prometheus - custom dashboards, reduce visible data, see what is important 
2:22:50 Beyond Metrics - Logs, Tracing, OpenTelemetry 
2:31:28 OpenTelemetry demo deployment  - shop, website, Jaeger tracing, 
2:39:05 Discussion: Why traces? What's next 
2:45:35 Performance and Scaling  - data retention, long-term storage,  distributed scaling, GitLab.com SaaS production insights, 
2:53:50 Observability and Chaos Engineering 
2:56:06 Chaos Mesh 
2:58:10 DNS Chaos - demo exercise from KubeCon EU, leak app memory, verify alerts and SLOs
3:12:45 Take action from chaos experiments 
3:15:00 Future Observability - eBPF, auto-instrumentation with Cilium Tetragon, etc. 
3:17:30 SLOs and quality gates with Keptn
3:17:48 Security - Policies with Kyverno, Hardening (book recommendation: Hacking Kubernetes)
3:18:54 Your adventure - 
3:19:20 Q&A - https://o11y.love and outro with Saiyam and Michael 
```

### Practical Kubernetes Monitoring with Prometheus 

The [slides](https://docs.google.com/presentation/d/17XVCbiC4PZYvpreZINmhNltmT-DDCo3LjoaPgqpsxVo/edit) provide a 4+ hours workshop, more details are available [on Michael Friedrich's personal blog](https://dnsmichi.at/2021/09/14/monitoring-kubernetes-with-prometheus-and-grafana-free-workshop/). The following topics will be practiced:

- Monitoring, quo vadis puts the traditional monitoring in contrast to microservices.
- Prometheus and Grafana shares the basic knowledge on Prometheus, PromQL, Service Discovery and terminology required to understand.
- Kubernetes dives into understanding what to monitor, and how.
- Prometheus Operator dives into the concept of the package, and kube-prometheus installing a full stack. You'll dive into the UI of Prometheus, Grafana and the Alert Manager.
- K8s monitoring with Prometheus walks you through the - amazing - default Grafana dashboards, instructs you to deploy a Go demo app with the CRD ServiceMonitor, Container Metrics and kube-state-metrics exercises to practice PromQL queries.
- Advanced Monitoring practices with a Python app and own metrics, deployed to the GitLab container registry and to Kubernetes to query with PromQL in Grafana dashboards. Storage with Thanos/Cortex, Service Discovery is touched as well.
- Alerts and Escalations dives into the Alert Manager and rules, mapped into the PrometheusRule CRD.
- SLA, SLO, SLI keeps you busy with learning about Service Level Objectives for your production environment, providing thoughts on CI/CD quality gates with Keptn - and the OpenSLO spec, Pyrra and Sloth.
- Observability moves from Monitoring to metrics, logs, traces and beyond.
- Secure Monitoring discusses TLS, secret management, Infrastructure as code workflows, Container security and RBAC & policies.
- Ideas on more monitoring with Prometheus exporters, podtato-head, Chaos Engineering, etc.

A shorter version of the workshop [as a talk](https://docs.google.com/presentation/d/1EEBJFgeThlVEeC_E3tOYGicU2X0S9vPGsba49EQSNwk/edit) was provided by Michael Friedrich at PromCon NA 2021, a zero day event at KubeCon NA.

[![](https://img.youtube.com/vi/CyQNYT1ZQQ8/0.jpg)](https://www.youtube.com/watch?v=CyQNYT1ZQQ8 "PromCon NA: Practical Kubernetes Monitoring with Prometheus")

## Talks 

[![KubeCon EU: From Monitoring to Observability: Left Shift your SLOs with Chaos - Michael Friedrich, GitLab](https://img.youtube.com/vi/BkREMg8adaI/0.jpg)](https://www.youtube.com/watch?v=BkREMg8adaI)
[![Container Days: Confidence with Chaos for your Kubernetes Observability - Michael Friedrich, GitLab](https://img.youtube.com/vi/TR6MFRySllA/0.jpg)](https://www.youtube.com/watch?v=TR6MFRySllA)
[![Container Days: OpenTelemetry: The Vision, the Reality and How To Get Started - Dotan Horovits, Logz.io](https://img.youtube.com/vi/TKidZH2iCtw/0.jpg)](https://www.youtube.com/watch?v=TKidZH2iCtw)
[![Container Days: Cracking Microservices Performance Issues with Distributed Tracing - Dotan Horovits](https://img.youtube.com/vi/vmmjIOwcqWA/0.jpg)](https://www.youtube.com/watch?v=vmmjIOwcqWA)
[![Container Days: Distributed applications and Kubernetes - Matthias Haeussler](https://img.youtube.com/vi/2y2dLuDTeBs/0.jpg)](https://www.youtube.com/watch?v=2y2dLuDTeBs)

Past talks:

- [Chaos Carnival 2022: From Monitoring to Observability: Left Shift your SLOs with Chaos](https://www.youtube.com/watch?v=RDy5-VAGaDs&t=112s)
- [All Day DevOps 2021: From Monitoring to Observability: Left Shift your SLOs](https://docs.google.com/presentation/d/1nTpngPtzoOgUu74b1ibDhmxYTwAocxn0/edit)
- [All Day DevOps 2020: From Monitoring to Observability: Migration Challenges from Blackbox to Whitebox](https://docs.google.com/presentation/d/1N5DpAryFp0mSwoyvPge41tjOfc4DszL1/edit)


## Meetups 

- [SLOconf Monthly](https://www.meetup.com/sloconf-monthly/), former SRE meetup. 
- [#EveryoneCanContribute cafe meetup](https://everyonecancontribute.com/)