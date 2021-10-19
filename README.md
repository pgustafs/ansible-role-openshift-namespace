openshift-namespace
===========

Basic description for openshift-namespace

Requirements
------------

Ansible 2.9 or higher

Red Hat Enterprise Linux 8 or equivalent

Valid Red Hat Subscriptions

Role Variables
--------------

Currently the following variables are supported:

### General

* `openshift-namespace_var_name` - var\_name description

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: openshift-namespace-servers
  roles:
    - role: openshift-namespace
```

License
-------

MIT

Author Information
------------------

Author Name <peter.gustafsson6@gmail.com>
