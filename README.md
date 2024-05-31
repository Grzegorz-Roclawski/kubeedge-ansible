# Overview
This is an Ansible project for creating Kubernetes cluster and KubeEdge infrastructure on it.

### Supported distributions:
* Ubuntu 22.04

### How to use:
1. Fill out *inventory.yml* file with your data.
2. Run *deploy_kubernetes.sh* to deploy Kubernetes cluster on your master and prepare your worker for futher deploy.
3. Run *deploy_kubeedge.sh* to create KubeEdge infrastructure on your cluster.

Project imported from: https://gitlab.com/rndan/infrastructure/ansible
