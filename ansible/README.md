## Ansible Module for installation Keepalived for Kubernetes
​ 
#### Prerequisite

- ansible 2.9 
- vim

### 1.) Create Directory for KeepAlived 
```shell 
mkdir -p /data/ansible/keepalived/source/
cd /data/ansible/keepalived/
vi install-keepalived.yaml.yaml
vi inventory
```
### 2.) Run Ansible Playbook  
```shell 
ansible-playbook -i inventory install-keepalived.yaml
```

### 3.) Limitation
```
Cannot use this playbook for HA Proxy [Only at Kubernetes Master Machine]
```
