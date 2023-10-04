# Ansible-skeleton
The purpose is to provide a folder structure for a new project.

## What is included
- Folder structures and placeholder files.
- Example role
- Inventories for multiple environments.

## Running example-playbook
To run the example-playbook against a running vagrant machine. Run this command in the root-directory of the project.
```ansible-playbook -i inventories/test/hosts example-play.yml```
