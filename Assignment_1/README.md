# DevOps

## Assignment 1

### Question
```
Guidelines Assignments
● must be completed individually.
● Take a look on other referrals from Ansible galaxy and submission should be made by
yourself.
● Please share code via individual github repository.
Requirements
The following files should be included in your submission
1. inventory file
2. site.yml the
3. main playbook file
4. Apache Hadoop 3.0.0 Installation file
5. Implement handlers to start and stop services
Task:
You need to write an Ansible role to install Apache Hadoop standalone cluster on your vm
instance (If required we will provide AWS vm) Ansible Playbook for Apache Hadoop installation.
You need to install Apache Hadoop on any Linux operating system at this time. Please include
all dependencies to complete this installation and you may refer other hadoop installation docs
for reference.
Note: If required we will provide AWS server for your work or you may use your laptop and
install vmware to complete this assignment
Vmware for windows:
https://my.vmware.com/web/vmware/info?slug=desktop_end_user_computing/vmware_workstat
ion/10_0
Hadoop Install:
https://hadoop.apache.org/docs/r3.0.3/hadoop-project-dist/hadoop-common/SingleCluster.html
```

### Solution
Playbook has 2 roles which performs below functions
- Setting up Hadoop 3
- Setting up Service Handler and starting Service

#### Ansible Command to execute Playbook
```
ansible-playbook -i hosts site.yml
```
