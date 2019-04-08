# litespeed_munin

A set of munin-plugins to monitor LiteSpeed updated work under CentOS 7.

Forked from https://github.com/burner1024/munin-litespeed

Might need to add

```
[litespeed_*]
# env.log   /var/log/httpd/domains/*.log
user root
```

to `/etc/munin/plugin-conf.d/munin-node`

