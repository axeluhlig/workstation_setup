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

### Oh My Zsh
```
$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### ToDo
- Create src directory
- Clone this repo
