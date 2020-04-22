# Collection of Ansible playbooks for Nginx Plus

Author: James Jones <jam.jones@nginx.com>

## Usage

### Prerequisites
- Nginx Plus repo access cert and key


### Setup
1. Clone repo
2. Copy your Nginx Plus customer cert and key to './certs'

### To Run a Playbook
  Execute command: `ansible-playbook -i ./configs/ansible/nodes.conf <playbook>`
