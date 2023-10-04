# Ansible-skeleton
The purpose is to provide a folder structure for a new project.

Folder structure in this skeleton is somewhat opinionated. Ansible provides alternative structures.

See [Ansible best practises](https://docs.ansible.com/ansible/latest/user_guide/playbooks_best_practices.html#directory-layout) for more information.

## What is included
- Folder structures and placeholder files.
- Example role
- Inventories for multiple environments.

## Running example-playbook
To run the example-playbook against a running vagrant machine. Run this command in the root-directory of the project.
```ansible-playbook -i inventories/test/hosts example-play.yml```
