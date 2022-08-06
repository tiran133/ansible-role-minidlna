Ansible Minidlna Role
=========

Downloads and compiles minidlna from source. See
https://sourceforge.net/projects/minidlna/

Requirements
------------

None

Role Variables
--------------

```
version: "1.3.0"
minidlna_port: "8200"
minidlna_server_name: "Minidlna Media Server2121"
```
Dependencies
------------

- community.general.ufw

Example Playbook
----------------

    - hosts: servers
      roles:
         - minidlna

License
-------

MIT

Author Information
------------------

Tiran133
