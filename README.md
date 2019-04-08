# munin-litespeed

A set of munin-plugins to monitor LiteSpeed updated for CentOS 7.

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

# Installation

Simple if you have `git` installed:

```
cd /etc/munin/plugins
git clone https://github.com/poralix/munin-litespeed.git
mv munin-litespeed/litespeed_* .
rm -rf munin-litespeed/
chmod 755 litespeed_*
service munin-node restart
```

# Configuration

Might need to add

```
[litespeed_*]
# env.log   /var/log/httpd/domains/*.log
user root
```

to `/etc/munin/plugin-conf.d/munin-node`
