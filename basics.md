## links
https://kubernetes.io/docs/setup/production-environment/windows/intro-windows-in-kubernetes/
https://kubernetes.io/docs/setup/production-environment/windows/user-guide-windows-containers/'
https://docs.microsoft.com/en-us/virtualization/windowscontainers/manage-containers/hyperv-container

## FAQ
```
In order to run Windows containers, your Kubernetes cluster must include multiple operating systems, with control plane nodes running Linux and workers running either Windows or Linux depending on your workload needs.
```
```
Note: The Kubernetes control plane, including the master components, continues to run on Linux. There are no plans to have a Windows-only Kubernetes cluster.
```
```
Windows containers offer two distinct modes of runtime isolation: process and Hyper-V isolation.
```


## Basics
- production support from 1.14
- massages
```
Organizations with investments in Windows-based applications and Linux-based applications don’t have to look for separate orchestrators to manage their workloads, leading to increased operational efficiencies across their deployments, regardless of operating system.
```
