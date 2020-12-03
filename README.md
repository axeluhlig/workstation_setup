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

### Store git credentials
```
git config --global credential.helper store
```

### ToDo
- Create src directory
- Clone this repo
