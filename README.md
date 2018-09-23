[![Galaxy](https://img.shields.io/badge/galaxy-dockpack.base__gradle-blue.svg?style=flat)](https://galaxy.ansible.com/dockpack/base_gradle)[![Build Status](https://api.travis-ci.org/dockpack/base_gradle.svg)](https://travis-ci.org/dockpack/base_gradle)


base_gradle
=========

Gradle - Tool to build Java projects. Tis is an ansible-role to install it.

Requirements
------------

This role was built for Ubuntu Trusty or RedHat systems like RHEL 6, Centos 6.
It depends on dockpack.base_java8.

Role Variables
--------------

    gradle: 1.10.1
    gradle_base: "/opt"

Dependencies
------------

Gradle needs Java8. This role depends on dockpack.base_java8, which will be installed automatically if you use this one.


Example Playbook
----------------
For a complete example with this role check out my buildserver:
git clone https://github.com/bbaassssiiee/buildserver.git

Example of how to use this role:

    - hosts: servers
      roles:
         - { role: dockpack.base_gradle }

License
-------

MIT

Author Information
------------------
Bas Meijer @bbaassssiiee
