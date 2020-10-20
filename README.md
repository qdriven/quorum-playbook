# Ansible Playbook Template

Script to init Ansible Playbook Projects.


- Init Workspace

```sh
sh init_workspace.sh
```

- Create Role

```sh
sh create_role.sh
```

## Using  SSH agent

Start the ssh-agent in the background.

```sh
eval "$(ssh-agent -s)"
```
Add private key to ssh agent 

```sh
ssh-add ~/.ssh/id_rsa
```