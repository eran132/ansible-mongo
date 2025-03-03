# MongoDB Ansible Deployment

## Setup

1. Copy `inventory.ini.template` to `inventory.ini`
2. Edit `inventory.ini` with your MongoDB server details
3. Run the playbook: `ansible-playbook -i inventory.ini main.yml`

## Required Variables

- `MONGODB_HOST`: Your MongoDB server IP address
- `MONGODB_USER`: SSH username for connection
- `SSH_KEY_PATH`: Path to your SSH private key
