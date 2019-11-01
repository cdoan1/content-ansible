# content-ansible

Use this project to setup a OCP based MCM cluster with content.

* this is an ansible project
* runs tasks against the localhost
* expects you to setup before hand
  * `oc login` to the target cluster
  * `cloudctl login` to the target cluster
  * `kubectl` cli
  * `helm` cli

## Content Catalog

- [ ] clusterimagepolicy - whitelists allowed docker repositories
- [ ] GRC policies - see design (here)
- [ ] inventory application
- [ ] ticketing application
- [ ] GRC policy controllers
- [ ] managed cluster 1
- [ ] managed cluster 2

