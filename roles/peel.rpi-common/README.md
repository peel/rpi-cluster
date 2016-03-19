rpi-common
=========

A base role for my Raspberry Pi configurations

Requirements
------------

None

Role Variables
--------------

    hostname = hell.codearsonist.com
    dns_nameservers:
    - "8.8.8.8"
    - "8.8.4.4"

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: peel.pi-common, hostname: "hell.codearsonist.com" }

License
-------

BSD
