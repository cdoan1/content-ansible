# content-ansible

Use this project to setup a OCP based MCM cluster with content.

* this is an ansible project
* runs tasks against the localhost
* expects you to setup before hand
  * `oc login` to the target cluster
  * `cloudctl login` to the target cluster
  * `kubectl` cli
  * `helm` cli

# Galaxy

```bash
ansible-galaxy collection install community.general
ansible-galaxy collection install community.kubernetes
```

```bash
pip install kubernetes openshift
```

# DSAL playbook

```bash
ansible-playbook -i inventory-dsal dsal.yml
```

# SPRINT playbook

```bash
ansible-playbook -i inventory-sprint sprint-demo.yml
```
