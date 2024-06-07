Role Name
=========

Vector role

Role Variables
--------------

vector_version - Версия Vector.
vector_config - Параметры конфига Vector. 

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - role: vector-role
          vars: 
            vector_version: "0.38.0"
            vector_config:
              sources:
              transforms:
              sinks:

License
-------

MIT

Author Information
------------------

Spasman
