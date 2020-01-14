# docker-swarm
Docker swarm cluster - Ansible role

## How to use this Role

Clone the repository to your roles folder

move docker-swarm.yml file to your `playbook` folder

create hosts files
eg:
```code
[docker-swarm-managers]
10.10.10.10
10.10.10.11
10.10.10.12
[docker-swarm]
10.10.10.10
10.10.10.11
10.10.10.12
```

Run the play book
```code
ansible-playbook -i hosts docker-swarm.yml
```
You can find detailed description here [https://devopsbyte.com/create-a-docker-swarm-cluster-using-ansible/]
