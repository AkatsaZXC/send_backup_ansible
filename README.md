# Sending backup to server via Ansible

This script dedicated for sending backup files to your server

Update file 'hosts' with your credentials, 'backups.yml' with your paths and use script via
'sudo ansible-playbook backups.yml -K'.
Key '-K' is for switching to super-user mode inside server.
