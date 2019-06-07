Hostname
=========

Ansible role to set hostname.

Requirements
------------

None

Role Variables
--------------
```
hostname_hostname
```

Dependencies
------------

None

Example Playbook
----------------

```yml
- hosts: servers
  vars:
    hostname_hostname: example.com
  roles:
     - gavika.hostname
```

License
-------
Apache

Author Information
------------------
Sudheer Satyanarayana

* Gavika: https://www.gavika.com
* Blog: https://www.techchorus.net
* Twitter: https://www.twitter.com/bngsudheer
* Github: https://github.com/bngsudheer
