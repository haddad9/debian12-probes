## ✅ sudo not available for another user (only for root)  
[stackoverflow](https://stackoverflow.com/questions/47806576/username-is-not-in-the-sudoers-file-this-incident-will-be-reported)
```bash
# add this to User privilege specification in /etc/sudoers
...
root    ALL=(ALL:ALL) ALL
user_name ALL=(ALL) ALL
..
```

## pyenv error install new env✅ 
 solution: install prerequisites dependencies to [build python](https://github.com/pyenv/pyenv/wiki#suggested-build-environment)
```bash
sudo apt update; sudo apt install build-essential libssl-dev zlib1g-dev \
libbz2-dev libreadline-dev libsqlite3-dev curl git \
libncursesw5-dev xz-utils tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev
```

## ❌  rootless docker installation 
[docker-docs](https://docs.docker.com/engine/security/rootless/#prerequisites)
this is needed to run docker without root privelege

## ❌ make caps and shift available for custom shortcut
[github custom gnome keyboard for input source]( https://github.com/madhead/shyriiwook )

