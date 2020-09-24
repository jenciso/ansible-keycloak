# KEYCLOAK SERVER

## Install

```shell
ansible-playbook site-common.yml -i inventory
ansible-playbook site.yml -i inventory -e keycloak_host="keycloak.docs-planet.site"
```
