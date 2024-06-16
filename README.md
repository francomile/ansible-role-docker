# Ansible docker role

[![Lint Ansible roles](https://github.com/francomile/ansible-role-docker/actions/workflows/ansible_lint.yml/badge.svg)](https://github.com/francomile/ansible-role-docker/actions/workflows/ansible_lint.yml)

[![Release role to Ansible Galaxy](https://github.com/francomile/ansible-role-docker/actions/workflows/push_to_galaxy.yml/badge.svg)](https://github.com/francomile/ansible-role-docker/actions/workflows/push_to_galaxy.yml)

## Actions of the Role

* Install Docker and Docker Compose
* Setup `daemon.json`

## Common Usage

```yaml
roles:
  - {
    role: docker,
    tags: ["docker"]
    }
```

## Run the playbook

```shell
ansible-playbook -i inventory playbook.yaml --tags "docker"
```
