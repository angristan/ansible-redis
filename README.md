# Ansible role for Redis

[![CircleCI](https://circleci.com/gh/angristan/ansible-redis.svg?style=svg)](https://circleci.com/gh/angristan/ansible-redis)

This is a simple role that will install Redis on Debian/Ubuntu.

## Sample playbook

```yaml
---

- hosts: myhost
  roles:
    - name: redis
      tags: redis
```
