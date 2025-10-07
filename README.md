Install and configure my development box
=========

The role installs and configures my development box.

Role Variables
--------------

A list of the variables that need to be set can be seen below

Example Playbook
----------------

```yaml
- hosts: servers
  vars:
    devbox_user: dev
    vscode_enabled: true

  roles:
      - role: tychobrouwer.devbox

      - role: tychobrouwer.devbox
        vscode_arch: amd64
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
