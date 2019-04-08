# munin-litespeed

A set of munin-plugins to monitor LiteSpeed updated work under CentOS 7.

Forked from https://github.com/burner1024/munin-litespeed

# Repository

- https://github.com/poralix/munin-litespeed

# Author

Modified/patched by Alex S Grebenschikov (www.poralix.com):

- litespeed_connections
- litespeed_requests
- litespeed_throughtput

Written by Alex S Grebenschikov (www.poralix.com):

- litespeed_hits
- litespeed_requests_post

# Configuration

Might need to add

```
[litespeed_*]
# env.log   /var/log/httpd/domains/*.log
user root
```

to `/etc/munin/plugin-conf.d/munin-node`
