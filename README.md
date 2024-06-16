# docker role

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
