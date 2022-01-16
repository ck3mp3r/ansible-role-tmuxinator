Role Name
=========
tmuxinator

Requirements
------------

Role Variables
--------------
* `user`: the user tmuxinator with be installed and configured for.

Example Playbook
----------------

    - hosts: localhost
      connection: local
      roles:
         - { role: ck3mp3r.tmuxinator, user: john }

License
-------

MIT

Author Information
------------------

Christian Kemper | kemper.buzz
