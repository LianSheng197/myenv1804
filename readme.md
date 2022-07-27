### apt-installed
```bash
apt list --installed > apt-installed.txt
```

### apt-ppa
```bash
grep ^ /etc/apt/sources.list /etc/apt/sources.list.d/* > apt-ppa.txt
```

### dpkg-install-log
```bash
grep -i " install " /var/log/dpkg.log** > dpkg-install-log.txt
zgrep -i " install " /var/log/dpkg.log.**.gz >> dpkg-install-log.txt
```