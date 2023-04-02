# Nginx ansible playbook

This repository contains a ansible playbook that installs and starts nginx on target server from ansible server.

There are few prequisites that you need to make sure of before running this ansible playbook :- 

- Ansible should be installed on master server, you can check the installation by running the following command 

```
ansible --version
```

- Password less authentication should be confgured. So that master server can do the tasks in target server. For that you can try to add public ssh key for master in target. 


In order to execute the playbook, you can use this command :- 

```
ansible-playbook -i inventory nginx-playbook.yaml
```

