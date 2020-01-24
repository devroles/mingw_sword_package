[![Build Status](https://github.com/devroles/mingw_sword_package/workflows/Make%20zips/badge.svg)](https://github.com/devroles/mingw_sword_package/workflows)

MinGW SWORD Package
===========

Creates zip files of the SWORD utils and other related files for Windows
based off the MinGW SWORD packages available in the Fedora repositories

Requirements
------------

Ansible 2.7 or higher

Fedora Linux

Role Variables
--------------

Currently the following variables are supported:

### General

* `download_dest` - Directory into which to download the resulting files (must
  end with a '/' character). Defaults to CWD

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: mingw_target
  roles:
    - role: devroles.mingw_sword_package
```

License
-------

GPLv3

Author Information
------------------

Greg Hellings <greg.hellings@gmail.com>
