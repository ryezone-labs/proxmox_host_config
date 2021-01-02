# ryezone_labs.proxmox_host_config
=========

Applies common host configuration for Proxmox VE hosts.

Requirements
------------

Requires proxmoxer python library.

Role Variables
--------------

| variables | description |
| --- | --- |
| `versions.jq.version` | version of jq to install |
| `versions.jq.checksum` | hash of jq download |


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
---
- hosts: proxmox_hosts
  roles:
    - ryezone_labs.proxmox_host_config
  vars:
    versions:
      jq:
        version: 1.6
        checksum: "sha256:AF986793A515D500AB2D35F8D2AECD656E764504B789B66D7E1A0B727A124C44"
```

License
-------

GPL-2.0-or-later

Author Information
------------------

Esten Rye
- [LinkedIn](https://www.linkedin.com/in/estenrye/)
- [GitHub: estenrye](https://github.com/estenrye/)
- [GitHub: ryezone-labs](https://github.com/ryezone-labs)
