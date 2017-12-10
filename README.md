Ansible echo-sd callback plugin
====

This is a callback plugin of ansible for bringing 'suddenly death'.

# setup

install `echo-sd` binary to `/usr/local/bin` directory.

* [echo-sd](https://github.com/fumiyas/home-commands/blob/master/echo-sd)

and puts this plugin into `callback_plugins/` directory.

finally, write `ansible.cfg` as below:

```
[defaults]
stdout_callback = echo-sd
```

# execution

run `ansible-playbook` command.

```
(snip)
＿人人人人人＿
＞　echo-sd　＜
￣Y^Y^Y^Y^Y^￣
(snip)
```
