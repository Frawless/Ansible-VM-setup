Role name
=========
Role for install Rhea client.

[![Build Status](https://travis-ci.org/rh-messaging-qe/ansible-rhea-client.svg?branch=master)](https://travis-ci.org/rh-messaging-qe/ansible-rhea-client)
[![GitHub Issues](https://img.shields.io/github/issues/rh-messaging-qe/ansible-rhea-client.svg)](https://github.com/rh-messaging-qe/ansible-rhea-client/2issues)
[![GitHub Issues](https://img.shields.io/github/issues-pr/rh-messaging-qe/ansible-rhea-client.svg)](https://github.com/rh-messaging-qe/ansible-rhea-client/pulls)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Interconnect ansible role for install client based on RHEA library.

## Supported systems
CentOS 6/7 and RHEL 6/7 (only 64b versions!)

## Tests
For testing we use the [provision_docker](https://github.com/chrismeyersfsu/provision_docker) playbook.

### Requirements
* docker_host (by default on localhost)

### How to run tests
```bash
$ make test
```

## License
Apache 2.0

## Author Information
Messaging QE team @ redhat.com
