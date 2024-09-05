# Ansible
----------
## Configuration Management Tool:
### WHAT

- Terraform | Ansible
- Infra Provisioning tool | Configuration Management tool

### WHY
1. Manualy - 100servers (timeconsume, human-error) (10 command)
2. Shell Script - (server manage) - (4 command)
3. Conf Mgmt tool

- Ansible | Puppet | Chef
- Push Based mech | Pull based mech 
- Python | Rubby DSL
- SSH Connection | Agents Deployed on server

### HOW
- Install Ansible 
- Modules - python 

- syntax: ansible -i hosts all -u <user> --private-key=<private-key> -m <module>
- ansible-playbooks (yaml)
- Syntax to generate config file: 
    ansible-config init --disable > ansible.cfg
- Syntax to play the playbook:
    ansible-playbook -u ubuntu --private-key=idrsa playbook.yaml

- yaml - indentation specific 

- ansible-playbook -e URL=cli.cloudblitz.in -u ubuntu --private-key=../id_rsa 2.\ variables.
yaml

- facts: information