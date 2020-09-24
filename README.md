# KEYCLOAK SERVER

## Install

```shell
ansible-playbook site-common.yml -i inventory
ansible-playbook site.yml -i inventory -e keycloak_host="sso-lab.docs-planet.site"
```
