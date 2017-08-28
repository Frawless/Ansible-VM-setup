.PHONY: package_install clean

all: setup

setup:
	ansible-playbook -i inventory start.yml

clean:
	docker rm -f $(containers) || true
	rm -rf ansible.cfg
	rm -rf roles/epel roles/nodejs roles/rh_register roles/rh_subscribe roles/provision_docker roles/cli-rhea roles/ansiblebit.oracle-java
