## docker-compose

[![Build Status](https://travis-ci.org/Oefenweb/ansible-docker-compose.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-docker-compose) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-docker--compose-blue.svg)](https://galaxy.ansible.com/Oefenweb/docker-compose/)

Set up (the latest or a specific version of) [Docker Compose](https://docs.docker.com/compose) in Debian-like systems.

#### Requirements

None

#### Variables

* `docker_compose_version` [default: `1.7.0`]: Version to install
* `docker_compose_install_prefix` [default: `/usr/local/bin`]: Install prefix

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - docker-compose
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-docker-compose/issues)!
