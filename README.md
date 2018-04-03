Basic server tools
=========

Basic server tools linux

Requirements
------------

S.O. RedHat, CentOS, Debian, outhers S.O. Linux.

Role Variables
--------------

That role install tools basic for a well operation in server linux. The tools that are instaled: 

Dependecies Installed (RedHat, CentOS)
- epel-release
- vim
- wget
- ntpdate
- firewalld
- htop
- atop
- puppet
- docker

Dependencies Installed (Debian, Ubuntu Server)
- build-essential
- vim
- htop
- wget
- atop
- ntpdate
- puppet
- docker

Changes
- It's change port default ssh to 22 from 41442
- Disabled selinux
- Add rule in firewall for accept conections on port 41442 (ssh)


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

Álvaro Bacelar

