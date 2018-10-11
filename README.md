# ansible-mac-setup
Simple Mac setup via ansible

This simple ansible playbook installs most of the software I use on Mac.

*Todo's*
- configuration should be automated too

## Installation
1. Install apple command line tools (xcode-select --install)
2. Install ansible with setup.sh (or http://docs.ansible.com/intro_installation.html)
3. Run `run ansible-galaxy install -r requirements.yml` to install required ansible roles
4. Run `ansible-playbook main.yml -i inventory -K` inside this directory (root password required)
