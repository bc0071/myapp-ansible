# myapp-ansible
Update for my own exercise

## Install ansible on Jenkins master
```
$ yum-config-manager --enable epel
$ sudo yum install ansible
```
## Install 'ansible' plugin in Jenkins
Manage Jenkins -> Plugin -> Available: search 'ansible'

Install 'Ansible' without restart

## Add Ansible in Global Tool Configuration
Manage Jenkins -> Global Tool Configuration; Add Ansible

```
Ansible
  Name: 
  Path to Git executable: 
```
## Jenkins Pipeline
