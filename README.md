# My Ansible Playbooks

## Macbook Pro

```
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ brew install git ansible
$ git clone https://github.com/amaotone/ansible-playbooks.git
$ cd ansible-playbooks
$ ansible-playbook macbook.yml
```

to run a specific role → `$ ansible-playbook macbook.yml --tags hoge`
