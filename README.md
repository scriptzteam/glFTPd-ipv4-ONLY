# glFTPd-ipv4-ONLY
Disable ipv6, use only ipv4!

```
Edit /etc/systemd/system/glftpd.socket -> ListenStream=Y.O.UR.ipv4:PORT

systemctl enable glftpd.socket
systemctl start  glftpd.socket
systemctl restart glftpd.socket
systemctl status glftpd.socket
```

:]
