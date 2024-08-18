# homelab-ansible

### Prepare Debian installation
`ansible-playbook -i inventory.ini debian.yml --vault-password-file=vault.txt`

Prerequisites:
- one sudo user
- partitioned and mounted netstorage disk 
