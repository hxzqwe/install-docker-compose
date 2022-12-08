# Ansible install docker-compose

## Role Variables

| Variable      | Required | Default                                                      | Comments               |
| ------------- | -------- | ------------------------------------------------------------ | ---------------------- |
| version       | Yes      | 1.29.2                                                       | docker-compose version |
| x86_64_sha256 | Yes      | f3f10cf3dbb8107e9ba2ea5f23c1d2159ff7321d16f0a23051d68d8e2547b323 | sha256 file hash       |

## Example Playbooks

```yaml
- hosts: dockerhosts
  remote_user: root

  roles:
    - install-docker-compose
```
