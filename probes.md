### ( sudo not available for another user (only for root) )[https://stackoverflow.com/questions/47806576/username-is-not-in-the-sudoers-file-this-incident-will-be-reported]

```bash
# add this to User privilege specification in /etc/sudoers
...
root    ALL=(ALL:ALL) ALL
user_name ALL=(ALL) ALL
..
```
