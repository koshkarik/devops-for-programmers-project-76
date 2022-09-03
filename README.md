### Hexlet tests and linter status:

[![Actions Status](https://github.com/koshkarik/devops-for-programmers-project-76/workflows/hexlet-check/badge.svg)](https://github.com/koshkarik/devops-for-programmers-project-76/actions)

### Deployed app:
[koshkarik.xyz](https://koshkarik.xyz)

### Prerequisites:
- Install Ansible
- Install Make
- Create secret vault-password file and place it in repo root.
- Install roles and collections with `make install`
- Add server ips's in inventory.ini
- Setup servers with `make prepare-servers`
- Run `make decrypt` to decrypt vault
- Add env variables in `vault.yml` , `vars.yml`, `templates/env.j2`
- Deploy `make deploy`


