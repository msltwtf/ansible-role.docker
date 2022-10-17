# Ansible Role: docker

[![CI](https://github.com/msltwtf/ansible-role.docker/actions/workflows/ci.yml/badge.svg)](https://github.com/msltwtf/ansible-role.docker/actions/workflows/ci.yml)

# Requirements

None.

# Role Variables

Available variables are listed below, along with default values from `defaults/main.yml`

| Variable       | Default                     | Comment                                  |
| :------------- | :-------------------------- | :--------------------------------------- |
| `docker_users` | `["{{ ansible_user_id }}"]` | Users that will be added to docker group |

# Dependencies

None.

# Example Playbook

```yaml
- hosts: all
  roles:
    - msltwtf.docker
```

# License

MIT
