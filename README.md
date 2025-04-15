# Instructions for setting up my homelab

There are three playbooks: `base_setup.yml`, `base_docker.yml`, `base_vm.yml`. They need to be applied in the provided order.

Example command to apply: `poetry run ansible-playbook -i inventory base_docker.yml -K --ask-vault-pass`