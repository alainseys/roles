linux-ssl
=========

This role will allow you to deploy your certificates from a centrelized repo to all of your servers 

Requirements
------------

Place your certificate in the files directory of this role then the role will distribute them

Role Variables
--------------

- {ssl_dest_dir}: the location where the ssl files will be deployed default on /etc/ssl on any linux system


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
