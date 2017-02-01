# Ansible-deploy-docker

Ansible playbook to build and deploy the giphy app with jenkins and docker

```
 $ ansible-playbook --inventory=inventory --extra-vars="tag_name=latest image_name=lsagastume/giphy-app baseimage=readytalk/nodejs container_name=giphy-app env=default port=3000 purpose=ansible owner=devops" main.yml
```
