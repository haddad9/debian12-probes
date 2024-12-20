## ✅ sudo not available for another user (only for root)  
[stackoverflow](https://stackoverflow.com/questions/47806576/username-is-not-in-the-sudoers-file-this-incident-will-be-reported)
```bash
# add this to User privilege specification in /etc/sudoers
...
root    ALL=(ALL:ALL) ALL
user_name ALL=(ALL) ALL
..
```

## ✅ 
```bash
sudo apt update
sudo apt upgrade
sudo apt install bash-completion
```

## ❌  rootless docker installation 
[docker-docs](https://docs.docker.com/engine/security/rootless/#prerequisites)
this is needed to run docker without root privelege

## ❌ make caps and shift available for custom shortcut
[github custom gnome keyboard for input source]( https://github.com/madhead/shyriiwook )

