** WIP : Ne pas utiliser **

Mon dotfiles

- configuration git -> ok
- configuration zsh -> ok
- configuration de php -> ok
- configuration de mysql -> ok
- configuration de pow -> ok
- configuration de phpcs
- configuration de sublimetext

# Pré-requis

Installation de XCode, Homebrew et ansible

# Installation

```
git clone git@github.com:benji07/dotfiles ~/dotfiles
cd ~/dotfiles
ansible-playbook -i hosts -K local.yml
```

