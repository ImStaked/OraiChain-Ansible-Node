# Oraichain-Ansible-Node

#### Install Ansible 
```pipx install ansible-core```

#### Create ssh key to access oraid host
```ssh-keygen -t ed25519```

#### Add ssh key to oraid host
```ssh-copy-id -i ~/.ssh/ed25519 user@oraidhost```

### Important Files
```config/inventory.yml```  
List of host ips to take action on 

```config/ansible.cfg```  
Ansible configuration. Requires ssh key path

```playbooks/roles/validator/defaults/main.yml```  
node setting and other configuration


