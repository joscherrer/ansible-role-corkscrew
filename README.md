ansible-role-corkscrew
=========

Installs corkscrew from source

Requirements
------------

Git

Role Variables
--------------

```
corkscrew_force_install: false
corkscrew_install_version: "v2.0"
prefix: "/usr/local"
```

Dependencies
------------

`geerlingguy.git`

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - role: ansible-role-corkscrew

License
-------

Apache 2.0

Author Information
------------------

Jonathan Scherrer