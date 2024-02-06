## Nebula playbook

Simple playbook to install and configure Nebula mesh network on host.

## Requirements

- create the config per node under `config/{{inventory_hostnam}}`
- prepare the certificate signing key, and certificates per nodes and store the under `config`
  - filename should match the inventory hostname
- set the following variables:
  - `nebula_src_url` to the release url you wand to deploy
  - `nebula_unit_url`to the service unit url you want to deploy
