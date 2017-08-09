# docker-install. Boring but useful

Install the latest docker engine.


## Example Playbook

```
  - hosts:
      - myhost.blahblah.
    sudo: yes
    gather_facts: true

    roles:
      - { role: marcelocorreia.docker-install, tags: ['install','hashicorp','consul', 'dnsmasq','config']}

```

## Default variables

```
docker_user: docker
docker_group: docker
```
