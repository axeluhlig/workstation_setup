Ansible scripts to setup a fresh Ubuntu focal machine for coding

## Intial setup

### Install Ansible
```
sudo apt update 
sudo apt upgrade
sudo apt install ansible
```

### Run Ansible
```
export ANSIBLE_FORCE_COLOR=true
ansible-galaxy collection install community.general
sudo -E ansible-pull -U https://github.com/axeluhlig/workstation_setup.git
```

### Aftermath
```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" # in case zsh did not yet show up. A reboot is also necessary to make it the default for every new terminal
git config --global credential.helper store # storing git credentials
```
