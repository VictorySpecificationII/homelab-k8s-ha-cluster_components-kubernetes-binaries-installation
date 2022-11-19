# homelab-k8s-ha-cluster_components-kubernetes-binaries-installation
Playbook that installs Kubernetes (kubectl, kubeadm, kubelet, podman) binaries to machines.

# How to use

 - If using as part of a Kubeadm deployment:

```
ansible-playbook -i hosts playbook.yaml -k
```

 - If using as part of a Kubespray deployment:

```
ansible-playbook -i hosts playbook.yaml --tags "kubespray" -k
```
