Ansible-kubernetes
==================

Creating and listing some resources from a Kubernetes cluster using Ansible

Usage
-----

This script runs on localhost.

Pre-requisites:
```
pip3 install openshift
ansible-galaxy collection install community.kubernetes
```

Create kubeconfig to `/tmp/kubeconfig`

Then run the playbook:
```
ansible-playbook -i inventory read-from-kubernetes.yml
```