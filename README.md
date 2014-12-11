## Install

```
vagrant plugin install dotenv
vagrant up
```

## Ssh

Add below:
```
# ~/.ssh/config
Host mouselocal
  HostName 192.168.33.10
  User vagrant
  IdentityFile ~/.vagrant.d/insecure_private_key
```

https://github.com/metarubygems/jack-rabbit
