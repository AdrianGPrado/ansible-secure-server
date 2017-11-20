Secure Server
=========

Role to secure the server. It performs the following operations:

  - Creates a user that is different from root. And that can connect using ssh without using password.
  - Configures SSH config file.
  - Configures Uncomplicated Firewall to only accept ssh connections.

Requirements
------------

None

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: AdrianGPrado.secure-server, x: 42 }

License
-------

BSD

Author Information
------------------

[Adrian G Prado](https://github.com/AdrianGPrado).
