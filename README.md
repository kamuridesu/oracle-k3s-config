# oracle-k3s-config
Description for each configuration for my Oracle k3s setup

This project was done as an experiment to setup K3s in a production environment, as well to give high availability to some of the services I run. 

The first config repo contains some Terraform configurations to setup the infrastructure, such as VNCs, subnets, security lists and Virtual Machines:

- [https://github.com/kamuridesu/oracle-k3s-terraform](https://github.com/kamuridesu/oracle-k3s-terraform)

The second config repo contains Ansible playbooks with roles for control plane and agent nodes:
- [https://github.com/kamuridesu/ansible-oracle-k3s](https://github.com/kamuridesu/ansible-oracle-k3s)

The next config repo contains Anisble playbooks to add applications entries to HAProxy LB:
- [https://github.com/kamuridesu/ansible-haproxy](https://github.com/kamuridesu/ansible-haproxy)

The files from ArgoCD (applications, services, etc) are here:
- [https://github.com/kamuridesu/argocd-apps-test-helm](https://github.com/kamuridesu/argocd-apps-test-helm)
