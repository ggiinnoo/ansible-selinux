Selinux
=========

Change the setup of selinux using this role

Requirements
------------

None

Role Variables
--------------

    selinuxConf
    selinuxPolicy
    selinuxState


Dependencies
------------

Some os from the centos range.

Example Playbook
----------------

    ---
    - name: Setting selinux state
      hosts: all
      roles:
        - selinux
License
-------

BSD

Author Information
------------------

    Creator: Gino Jansen
    Website: www.ginojansen.nl
