# My Ansible Playbooks

## For Macbook

```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
$ brew install git ansible
$ git clone https://github.com/kotapiku/ansible-playbook.git
$ cd ansible-playbook
$ ansible-playbook macbook.yml
```

to run a specific role → `$ ansible-playbook macbook.yml --tags hoge`
