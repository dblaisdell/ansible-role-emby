Role Name
=========
An Ansible role that installs Emby (https://emby.media/) on Ubuntu 16.04 

Requirements
------------
Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

## ansible.cfg
This role is designed to work with merge "hash_behaviour". Make sure your
ansible.cfg contains these settings

```INI
[defaults]
hash_behaviour = merge
```

Role Variables
--------------
N/A

Dependencies
------------
N/A

Example Playbook
----------------
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: rofrantz.emby }

License
-------
MIT

Author Information
------------------
Francisc Ungureanu
