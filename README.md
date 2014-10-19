** WIP : Ne pas utiliser **

# Pré-requis

Installation des command line tools, Homebrew et ansible

# Installation

```
git clone git@github.com:benji07/dotfiles ~/dotfiles
cd ~/dotfiles
ansible-playbook -i hosts -K local.yml
```

# FAQ

```
~/dotfiles/hosts --list [Errno 8] Exec format error
```

If you get this error to chmod the hosts file to 644
