# My playbook to provision my Macbook

## Installation

- Install Apple's command line tools 
```bash
$ xcode-select --install
```

- Install Ansible with `pip`
```bash
$ sudo easy_install pip
$ sudo pip install ansible
```

- Run Ansible for provisioning
```bash
$ ansible-galaxy install -r requirements.yml
$ ansible-playbook main.yml -i inventory -K
```