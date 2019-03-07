[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-puppet-ce.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-puppet-ce)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [Puppet](https://puppet.com/)
------------

Description
------------

 * Ansible for Puppet CE

Requirements
------------

 *

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - iac-ansible-puppet-ce
...    
```

License
-------

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
