# eBPF

## Overview

> Instead of relying on static counters and gauges exposed by the operating system, eBPF enables the collection & in-kernel aggregation of custom metrics and generation of visibility events based on a wide range of possible sources. 

- [ebpf.io](https://ebpf.io/)
    - [Infrastructure](https://ebpf.io/infrastructure) including the Linux Kernel, Compilers (LLVM, gcc), Libraries (Go, C/C++, Rust)
    - [Applications](https://ebpf.io/applications)

## Projects

### Observability

- [Pixie](https://px.dev/), Kubernetes observability for developers, auto-instrumented, scriptable.   
- [Coroot](https://coroot.com/), Kubernetes Observability, implements service maps using eBPF. 
- [Parca](https://www.parca.dev/), Continuous Profiling 
- [ebpf_exporter](https://github.com/cloudflare/ebpf_exporter), Prometheus exporter for custom eBPF metrics 
- [OpenTelemetry eBPF Collectors](https://github.com/open-telemetry/opentelemetry-ebpf), low level kernel telemetry data on a host Kernel, from the cloud or within a Kubernetes cluster.

### Security 

- [Cilium](https://cilium.io/), network connectivity security and observability
    - [Tetragon](https://github.com/cilium/tetragon)
- [Tracee](https://aquasecurity.github.io/tracee/latest/), Runtime Security and Forensics
- [Falco](https://falco.org/), Kubernetes threat detection engine. Use case example: Package dependency scanning with [GitLab Package Hunter](https://falco.org/blog/gitlab-falco-package-hunter/)

### SRE/DevOps 

- [Inspektor Gadget](https://www.inspektor-gadget.io/), A collection of eBPF-based gadgets to debug and inspect Kubernetes apps and resources 
- [Caretta](https://github.com/groundcover-com/caretta), instant Kubernetes service dependency map in Grafana, using VictoriaMetrics as backend. 
- [BumbleBee](https://github.com/solo-io/bumblebee), build, run and distribute eBPF programs using OCI images.

## Hot Topics

- [The Power of eBPF for Cloud Native Systems](https://cybersecurity-magazine.com/the-power-of-ebpf-for-cloud-native-systems/) is a comprehensive deep-dive into cloud-native, IoT and Edge computing, and ideas how to monetize eBPF. Suggest watching [Hello eBPF! Goodbye Sidecars](https://www.youtube.com/watch?v=ThtRT8dhu8c) by [Liz Rice](https://www.linkedin.com/in/lizrice/) as additional learning insight, and dive into [eBPF and its capabilities](https://medium.com/exness-blog/ebpf-and-its-capabilities-9a3a1dce3802). 
- [Learn how eBPF can help minimize "observability tax"](https://coroot.com/blog/minimizing-observability-tax)
- [eBPF: Why now, introduction and deep dive](https://whynowtech.substack.com/p/ebpf?sd=pf)
- [eBPF report by Liz Rice](https://isovalent.com/ebpf/)
- [Bypassing eBPF-based Security Enforcement Tools](https://www.form3.tech/engineering/content/bypassing-ebpf-tools)

## Learning Resources

eBPF learning story shared by Michael Friedrich in their talk ["From Monitoring to Observability: eBPF Chaos" at Config Management Camp 2023](https://go.gitlab.com/5vhjv1).

### Newsletters

- [eCHO newsletter](https://cilium.io/newsletter/)
- [opsindev.news newsletter](https://opsindev.news/)

### Books and blog posts

- [Learning eBPF](https://www.oreilly.com/library/view/learning-ebpf/9781098135119/) by [Liz Rice](https://www.linkedin.com/in/lizrice/), will be published in June 2023.
- [BPF Performance Tools (Book)](https://www.brendangregg.com/bpf-performance-tools-book.html)
- [How we diagnosed and resolved Redis latency spikes with BPF and other tools](https://about.gitlab.com/blog/2022/11/28/how-we-dia