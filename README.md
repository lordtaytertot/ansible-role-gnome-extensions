lordtaytertot.gnome-extensions
==============================

Manages GNOME Extensions

Requirements
------------
`gnome-shell` (tested against 48.2)

Role Variables
--------------
`gnome_extension_ids`: list of GNOME Extension IDs to be installed

Dependencies
------------
[GNOME](https://www.gnome.org/)

Example Playbook
----------------
```yaml
- hosts: servers
  roles:
     - { role: lordtaytertot.gnome-extensions, gnome_extension_ids: [ 517, 5470 ] }
```

License
-------

MIT
