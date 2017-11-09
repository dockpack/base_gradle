dockpack.gradle
=========

Gradle - To build Java projects.

Requirements
------------

This role was built for Ubuntu Trustym or RedHat systems like RHEL 6, Centos 6. It needs   dockpack.base_java8.

Role Variables
--------------

gradle: 1.10.1

gradle\_base: "/opt"

Dependencies
------------

Ant needs Java8. This role depends on dockpack.base_java8, which will be installed automatically if you use this one.



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
