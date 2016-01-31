# docker-install. Boring but useful

Install the latest docker engine.


## Example Playbook

```yml
---
  - hosts:
      - myhost.blahblah.
    sudo: yes
    gather_facts: true

    roles:
      - { role: marcelocorreia.docker-install, tags: ['install','hashicorp','consul', 'dnsmasq','config']}

```
