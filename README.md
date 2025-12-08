# Ansible-kit

A collection of reusable and modular Ansible roles and playbooks I created.

---

### Roles
| Role | Description |
| ------ | ------ |
| [Ansible-APHAproxy](https://github.com/chxperiments/ansible-kit/tree/main/roles/ansible-APHaproxy)  | Active Passive HAPROXY Deployement with metrics |
| [Ansible-Containerd](https://github.com/chxperiments/ansible-kit/tree/main/roles/ansible-containerd) | Deploy Containerd engine |
| [Ansible-GitOps](https://github.com/chxperiments/ansible-kit/tree/main/roles/ansible-gitops) | Deploy and configure ArgoCD on K8S Clusters |
| [Ansible-k8s-preflight](https://github.com/chxperiments/ansible-kit/tree/main/roles/ansible-k8s-preflight) | Preflight tasks for kubernetes|
| [Ansible-k8s-Setup](https://github.com/chxperiments/ansible-kit/tree/main/roles/ansible-k8s-setup) | Setup Kubernetes |


--- 

### Playbooks

| Playbook | Description |
| ------ | ------ |
| [AWX Resources Migrations](https://github.com/chxperiments/ansible-kit/blob/main/playbooks/awx_resource_migrations.yml) | Export/Import your AWX resources (inc; Users, RBAC, Job Templates, Workflows, etc...) |
| [AWX User Configuration](https://github.com/chxperiments/ansible-kit/blob/main/playbooks/awx_user_config.yml) | Create and configure AWX user on remote servers |
| [Root Password Rotation](https://github.com/chxperiments/ansible-kit/blob/main/playbooks/root_password_rotation.yml) | Generates (locally) and changes root password on all servers |
