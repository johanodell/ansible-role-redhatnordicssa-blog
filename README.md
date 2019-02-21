ansible-role-redhatnordicssa-blog
===========

Basic description for ansible-role-redhatnordicssa-blog

Requirements
------------

Ansible 2.5 or higher

Red Hat Enterprise Linux 7 or equivalent

Valid Red Hat Subscriptions

Role Variables
--------------

Currently the following variables are supported:

### General

* `ansible-role-redhatnordicssa-blog_var_name` - var\_name description

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: ansible-role-redhatnordicssa-blog-servers
  become: true
  roles:
    - role: rhnordics.ansible-role-redhatnordicssa-blog
```

License
-------

GPLv3

Author Information
------------------

Author Name <pgustafs@redhat.com>
