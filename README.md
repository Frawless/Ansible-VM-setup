Setup new VM by ansible
=========
[![Build Status](https://travis-ci.org/Frawless/ansible-vm-setup.svg?branch=master)](https://travis-ci.org/Frawless/ansible-vm-setup)

## Supported systems
CentOS 6&7 and RHEL 6&7

## Install following
--------------------------

- vim enhanced
- wget
- qpid-dispatch (Router implementation)
- cli-rhea (RHEA based client)
- amq-broker (Broker implementation)
- with all dependencies

## Requirements
------------

None.

## Tests
For testing we use the [provision_docker](https://github.com/chrismeyersfsu/provision_docker) playbook.

### Requirements
* docker_host (by default on localhost)

### How to run tests
```bash
$ cd test && make
```

## License
-------

Apache 2.0


## Author Information
------------------

Messaging QE team @ redhat.com
