Role Name
=========

Opensuse (Tumbleweed) configuration/hardening.

Requirements
------------

Assumes sle15-script-cis_server_l1.sh (or equivalent ansible) from scap-security-guide has been run.

Role Variables
--------------

N/A

Dependencies
------------

community.general collection

Example Playbook
----------------

    - hosts: all
      become: yes
      roles:
      - suse_server

License
-------

BSD

Author Information
------------------

- r7st (r7st.guru@gmail.com)
