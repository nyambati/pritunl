Pritunl VPN server
=========

This Ansible role enables you to install Pritunl VPN server with much ease

Role Variables
--------------
This role installs mongodb version 3.2 by default. However you can chnage it using mongodb_version variable
```
# change the version of mongodb, default 3.2
mongodb_version: 3.x

```

# Installation

To install run

```
$ ansible-galaxy thomas.pritunl
```

## Usage

Add the role to your playbook
```
 - hosts: servers
   roles:
      - { role: username.rolename, mongodb_version: 3.2 }
```

License
-------
This role is released under the MIT license
