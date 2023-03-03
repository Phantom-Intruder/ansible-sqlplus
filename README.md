sqlplus
=========

Role that does a full installation of sqlplus by downloading and installing necessary dependencies and packages.

Requirements
------------

All requirements are included in role.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Using the role is simple:

    - hosts: sqlplus
      become: true
      roles:
        - sqlplus

A more comprehensive example of this role being used can be found [here](https://github.com/Phantom-Intruder/infrastructure-configs/tree/master/ansible/jenkins) in this [role](https://github.com/Phantom-Intruder/infrastructure-configs/blob/master/ansible/jenkins/roles/slave/tasks/main.yaml)

License
-------

BSD

Author Information
------------------

[Mewantha Bandara](https://www.linkedin.com/in/mewantha-bandara/)