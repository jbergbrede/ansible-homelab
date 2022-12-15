# ansible-homelab
Ansible playbooks for my homelab

## Cheatsheet

### Execute command on group of machines:

`ansible <host-group> -i <inventory> -m <command>`

for example: `ansible unifi -i staging -m ping`

### Run ansible playbook:

`ansible-playbook -i <inventory> <playbook>.yml`

for example: `ansible-playbook -i production homebridge.yml`