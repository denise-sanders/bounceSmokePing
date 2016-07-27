Role Name
=========

This is for slaves that need to be restarted. We discovered that for our set up, the best way to restart smokeping is to kill currently running processes, stop and restart the smokeping service.

Requirements
------------

Make sure you have a smokeping inxtance on the server you want to run it on. Also, this will kill all of your processes that have the name "smoke" in them, so make sure you dont have any of those.

Role Variables
--------------

No variables!

Dependencies
------------

No dependencies!

Example Playbook
----------------

See the main.yml at the project root!

License
-------

BSD

