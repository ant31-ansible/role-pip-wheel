PIP-WHEEL
==========

This role prepare a bundle/wheel with all dependecies to easily install a python packge to machines without internet access.

It downloads the python package's dependencies localy, prepare a tarball, send it to the target host and use pip to install them all.

Requirements
------------

 - python-pip

Role Variables
--------------
Define the list of packages to install as follow:

```yaml
---
wheel_home: /var/cache/wheelhouse
```

Dependencies
------------
 - None

Example Playbook
----------------
```yaml


```
License
-------

MIT
