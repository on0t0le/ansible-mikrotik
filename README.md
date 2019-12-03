### Simple RouterOS commands
###### Pre-flight steps
Before you begin create inventory
```sh
cp inv/hosts.dist inv/hosts
```
Fill-in all required data in inv/hosts file.

###### Start deployment
To start deployment on your router
```sh
ansible-playbook -i inv/hosts deploy.yml
```