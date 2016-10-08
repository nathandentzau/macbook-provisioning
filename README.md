# My playbook to provision my Macbook

## Installation

  1. Install Apple's command line tools 
    ```bash
    $ xcode-select --install
    ```
  2. Install Ansible with `pip`
    ```bash
    $ sudo easy_install pip
    $ sudo pip install ansible
    ```
  3. Run Ansible for provisioning
    ```bash
    $ ansible-galaxy install -r requirements.yml
    $ ansible-playbook main.yml -i inventory -K
    ```