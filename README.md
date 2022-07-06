Vector Role
=========

Install Vector

Requirements
------------

Tested on Centos 7

Role Variables
--------------

`defaults/main.yml`

|        Variables        |       Description        |                           Default                            |
| :---------------------: | :----------------------: | :----------------------------------------------------------: |
|     vector_version      | Version Vector packages  |                            0.22.1                            |
|       vector_home       |     Vector directory     |                         /tmp/vector                          |
|       vector_url        |        Vector URL        | https://packages.timber.io/vector/{{ vector_version }}/vector-{{ vector_version }}-1.x86_64.rpm |
|       vector_user       |       Vector user        |                            vector                            |
|      vector_group       |       Vector group       |                            vector                            |
| vector_environment_file | Path to environment file |                     /etc/default/vector                      |



Dependencies
------------

No dependencies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - vector

License
-------

MIT

Author Information
------------------

Aleksei Iarin
