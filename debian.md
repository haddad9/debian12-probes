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

## Bluetooth earphone error poor quality ✅ 
**problems**: the default bluetooth profile connected to the OS is HSP
**solution**: change the bluetooth profile ro A2DPSink using [ SBC Codec ](https://askubuntu.com/questions/765233/pulseaudio-fails-to-set-card-profile-to-a2dp-sink-how-can-i-see-the-logs-and/773391#773391)



## ❌  rootless docker installation 
[docker-docs](https://docs.docker.com/engine/security/rootless/#prerequisites)
this is needed to run docker without root privelege

## ❌ make caps and shift available for custom shortcut
[github custom gnome keyboard for input source]( https://github.com/madhead/shyriiwook )

## ❌ mouse bluetooth device not detected in debian 12
- [ stack exchange link ](https://unix.stackexchange.com/questions/588252/how-do-i-pair-a-bluetooth-mouse-in-debian)
- problem: cannot pair and bt not detected
- cannot install bluez-tool but still need work around to build the binary from the [ repo ](https://github.com/khvzak/bluez-tools)
