# up-and-running

This is a role for my own use to set up my MicroOS box from a fresh installation.

## Requirements

Needs `community.general` collection.

## Example Playbook

```yaml
---
 - name: setup box
   become: true
   hosts: localhost
   roles:
    - {role: up-and-running}
```

License
-------

Unlicense
