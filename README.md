### Deploy Vanilla Kubernetes Development Environment

Tested on Ubuntu 18.
Requires ansible >= 2.5.1 to run.
Add user name who will be running the playbook to ./ansible.cfg
Add user name who will be running k8s to ./tasks/roles/k8s-master-and-worker/vars/main.yml

Run playbook to deploy a single node cluster locally:
```
ansible-playbook -i hosts/default-hosts tasks/deploy-k8s.yml
```
