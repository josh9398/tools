# DevOps Tooling Set
A list of useful tools used over times on different projects. Feel free to open PRs.

## Docker
### [nsenter](http://man7.org/linux/man-pages/man1/nsenter.1.html)
Run a program within the namespaces of other processes.
```bash
nsenter -t pid -n command
```

## Kubernetes
### CLI
#### [k9s](https://github.com/derailed/k9s)
Manage k8s in style with this CLI

#### [kubectx](https://github.com/ahmetb/kubectx)
   `kubectx` helps you switch between clusters back and forth.
   `kubens` helps you switch between Kubernetes namespaces smoothly.

### Plugins
#### [krew](https://github.com/kubernetes-sigs/krew)
Package manager for kubectl plugins.

### Debug
#### [capture](https://github.com/sysdiglabs/kubectl-capture)
Tool for container troubleshooting, performance tunning and security investigation.

#### [kail](https://github.com/boz/kail)
Kubernetes tail multiple pods on Kubernetes and multiple containers within the pod.



