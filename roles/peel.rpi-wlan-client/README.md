Role Name
=========

A brief description of the role goes here.

Requirements
------------

- peel.rpi-common

Role Variables
--------------

    client_interface = "wlan0"
    ssid = "LoremIpsum"
    password = "DolorSitAmet"

Example Playbook
----------------

    - hosts: pis 
      roles:
         - { role: peel.rpi-wlan-client, client_interface: "wlan0", ssid: "Lorem", password: "Ipsum" }

License
-------

BSD
