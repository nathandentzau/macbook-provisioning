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

### Manual configuration
Terminal

Terminal > Preferences > Gear Icon > Import
Select one of the themes located at osx/terminal/.
Set as default the profile with the materialshell theme selecting the profile and clicking on the Default button.
