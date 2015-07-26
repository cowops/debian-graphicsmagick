Debian-Graphicsmagick
=====================

GraphicsMagick is the swiss army knife of image processing.

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: loranger.debian-graphicsmagick }

Tasks
-----

  - Install [GraphicsMagick](http://www.graphicsmagick.org/)

License
-------

BSD