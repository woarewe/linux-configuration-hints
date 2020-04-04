```shell
adduser <username>
usermod -aG sudo <username>
chown -R <username>:<username> /home/<username>/
chown root:root /home/<username>
chmod 700 /home/<username>/.ssh
chmod 644 /home/<username>/.ssh/authorized_keys
```
