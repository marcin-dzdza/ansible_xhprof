Requires
- ansible,
- php 7.0 or later
- git
- composer
- nginx

- If necessary, modify vars below
- Run
```sudo ansible-playbook xhprof.yml```
- add xhgui_hostname to your /etc/hosts

If this is run for vagrant, run it from guest machine as vagrant user and add hostname to host machine /etc/hosts

To understand this script or to learn to use xhprof, use the following links:
- https://github.com/perftools/xhgui
- https://www.digitalocean.com/community/tutorials/how-to-set-up-xhprof-and-xhgui-for-profiling-php-applications-on-ubuntu-14-04
