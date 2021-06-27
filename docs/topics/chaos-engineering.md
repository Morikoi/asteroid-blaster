
# Chaos Engineering 

[Chaos Engineering](https://en.wikipedia.org/wiki/Chaos_engineering) describes the disciplicine of experimenting with a software system to ensure reliability and resiliency with unexpected conditions. Modern distributed architectures with microservices require chaos engineering frameworks and platforms to simulate production incidents and unexpected behaviour. 

Observability with [metrics](../metrics), [tracing](../tracing), [logs/events](../logs-events), etc. is needed to measure and observe the impact of chaos engineering. 

## Tools

### Chaos Mesh

- [Website](https://chaos-mesh.org/)
- [Documentation](https://chaos-mesh.org/docs/)

#### Facts

- Chaos Mesh is a [CNCF project](https://www.cncf.io/projects/chaosmesh/), and approved to [incubating in February 2022](https://www.cncf.io/blog/2022/02/16/chaos-mesh-moves-to-the-cncf-incubator/).

#### Hot Topics 

- [Simulating Clock Skew in K8s Without Affecting Other Containers on the Node](https://chaos-mesh.org/blog/simulating-clock-skew-in-k8s-without-affecting-other-containers-on-node/)
- [Kube Simplify: Kubernetes Observabiltty workshop](https://www.youtube.com/watch?v=sMEEVbZ4NFM&t=10405s) includes hands-on exercises with DNS Chaos 

[![DNS Chaos with Chaos Mesh exercise](../assets/images/chaos-engineering/kubesimplify_kubernetes_observability_workshop_chaos_mesh_dns_chaos.png)](https://www.youtube.com/watch?v=sMEEVbZ4NFM&t=10405s)

### Chaos Toolkit

- [Website](https://chaostoolkit.org/)
- [Documentation](https://chaostoolkit.org/reference/usage/install/)

#### Facts 

- Rich integration ecosystem to integrate with tools to inject probes. Can run [Pixie](https://chaostoolkit.org/drivers/pixie/), use [Toxyproxy](https://chaostoolkit.org/drivers/toxiproxy/), and more. 

#### Hot Topics 

- [Chaos Testing in GitLab PoC](https://gitlab.com/gitlab-org/gitlab/-/issues/368586)

### Litmus Chaos 

Litmus helps SREs and developers practice chaos engineering in a Cloud-native way.
