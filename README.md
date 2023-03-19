# ansible-playbook-workstation-rhel

```
dnf -y install git-core ansible-core

git clone https://github.com/leofranzen/ansible-playbook-workstation-rhel

cd ansible-playbook-workstation-rhel/
ansible-galaxy collection install community.general
ansible-playbook -i inventory/localhost.ini playbook.yml
```