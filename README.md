Role Name
=========

Adds ssh keys to the root account.


Role Variables
--------------

The variable `root_keys` should be a list of the ssh keys that should
be added to the root account.

Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-fgci-ssh-keys, tags: [ 'ssh' ] }

License
-------

MIT

Author Information
------------------

https://github.com/jabl
