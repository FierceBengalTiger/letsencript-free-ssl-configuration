# Download letsencript for free SSL
```shell
sudo git clone https://github.com/letsencrypt/letsencrypt /opt/letsencrypt
```

# Fix
```shell
export LC_ALL="C"
```


# GoTo 
```shell
cd /opt/letsencrypt
```

# Run lets encrypt to generate ssl certificate for your domain
```shell
./letsencrypt-auto certonly --standalone --email user@example.com -d your.domain.com
```
- > Change `user@example.com` and `your.domain.com` as per yours.

# Check files created or not
```shell
sudo ls /etc/letsencrypt/live/your.domain.com
```

# [Documentation of Ubuntu Server Setup](https://github.com/FierceBengalTiger/ubuntu-server-setup-script/)
