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
sudo ansible-pull -U https://github.com/axeluhlig/workstation_setup.git
```

### ToDos
- Add yamllint to programms to install
- Create src directory
- Clone this repo
- Setup git (email, username, creds)
