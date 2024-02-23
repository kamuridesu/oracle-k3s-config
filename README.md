# oracle-k3s-config
Description for each configuration for my Oracle k3s setup

This project was done as an experiment to setup K3s in a production environment, as well to give high availability to some of the services I run. 

The first config repo contains some Terraform configurations to setup the infrastructure, such as VNCs, subnets, security lists and Virtual Machines:

- [https://github.com/kamuridesu/oracle-k3s-terraform](https://github.com/kamuridesu/oracle-k3s-terraform)

The seconf config repo contains Ansible playbooks with roles for control plane and agent nodes:
- [https://github.com/kamuridesu/ansible-oracle-k3s](https://github.com/kamuridesu/ansible-oracle-k3s)
