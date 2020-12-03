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
sudo -E ansible-pull -U https://github.com/axeluhlig/workstation_setup.git
```

### ToDos
- Add yamllint to programms to install
- Create src directory
- Clone this repo
- Setup git (email, username, creds)
