Ansible Role: Jenkins CLI
=========================

An Ansible role that makes it easier to work with the Jenkins CLI.

    NOTE: This role is a work in progress. The original intention is to make it
    simpler to add Jenkins Slaves to the Master programmatically.

Role Variables
--------------

Dependencies
------------

No dependencies, but it is expected that Jenkins is already installed on the
machine(s) you plan to interact with. This role has been designed to work with
`geerlingguy.jenkins`

Example Playbook
----------------

    - hosts: jenkins_master
      roles:
         - { role: leifmadsen.jenkins-cli }

License
-------

Apache 2

Author Information
------------------

This role was created in 2016 by Leif Madsen.
