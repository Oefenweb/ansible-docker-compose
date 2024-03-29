## docker-compose

[![CI](https://github.com/Oefenweb/ansible-docker-compose/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-docker-compose/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-docker--compose-blue.svg)](https://galaxy.ansible.com/Oefenweb/docker-compose/)

Set up (the latest or a specific version of) [Docker Compose](https://docs.docker.com/compose) in Debian-like systems.

#### Requirements

None

#### Variables

* `docker_compose_version` [default: `v2.25.0`]: Version to install
* `docker_compose_install_prefix` [default: `/usr/local/lib/docker/cli-plugins`]: Install prefix

## Dependencies

None

## Recommended

* `ansible-docker` ([see](https://github.com/Oefenweb/ansible-docker))
* `ansible-docker-machine` ([see](https://github.com/Oefenweb/ansible-docker-machine))

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.docker-compose
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-docker-compose/issues)!
