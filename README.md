Hostname
=========

Ansible role to set hostname. This role is tested manually.

We're working on getting the automated tests to work. Till that time, the role
will be tagged as beta and not available on Galaxy.

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
