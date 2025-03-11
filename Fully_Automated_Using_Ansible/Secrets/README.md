This directory is reserved for storing sensitive data, including all passwords used in this task. For security reasons, the files in this folder were excluded from the upload and are not included in the repository.
- Files that should be included:
1. `ansible_course`: Private key for Ansible SSH connection
2. `ansible_course.pub`: Public key for Ansible SSH connection
- Files that are included **for demonstration**, but should be ignored:
1. `ansible_vault_password.txt`: Ansible Vault password used to encrypt the `vars/main.yml` file of the `dbserver` and `webserver` roles. Make sure to save this file in a secure place with the right file permissions.
