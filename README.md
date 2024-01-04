# django-ci-cd-NexusRegistry
## Description
This project is for hardening of the production server for 'DevopsHobbies' project and installing Traefik as reverse proxy and Nexus as docker private registry.
## Generate Treafik pass
```bash
echo $(htpasswd -nb user password) | sed -e s/\\$/\\$\\$/g
```
