# Ansible Config to easily configure and install my Xubuntu based VMs

## Usage

1. Install ansible: `apt-get install ansible`
2. Comment out all tasks you don't want in `main.yml`
3. Modify config.yml according to your needs
4. Run `ansible-playbook --ask-become-pass main.yml`
5. Type in your sudo password if you get asked for the `BECOME password`
