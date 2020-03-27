Ansible role `rasdaemon`
=========

An Ansible role for installing `rasdaemon` - daemon which reports hardware (memory) errors.
It is very simple role, which can be used as a template or for training, yet it does something useful.

Requirements
------------

CentOS/RHEL 7+ system, with rasdaemon package available.

Role Variables
--------------

Dependencies
------------

None so far.

Example Playbook
----------------

```
    - hosts: all
      roles:
        - { role: pauliusm.rasdaemon }
```

Testing
-------

Testing is quite interesting, as it requires real hardware.
Use [run-docker-tests.sh](tests/run-docker-tests.sh) to test some things in docker.

License
-------

BSD

Contributors
------------

- [Paulius Mažeika](https://github.com/pauliusm)
