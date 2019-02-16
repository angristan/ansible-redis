# Ansible role for Redis

This is a simple role that will install Redis on Debian/Ubuntu.

## Sample playbook

```yaml
---

- hosts: myhost
  roles:
    - name: redis
      tags: redis
```
