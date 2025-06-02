# Apache Deployment Playbook  
Ansible playbook to automate Apache HTTPd deployment on Red Hat/CentOS.  

## Usage  
1. Clone the repo:  
   ```bash
   git clone https://github.com/your-username/nominet-ansible-deployment.git
Update inventory.ini and vars.yml.

Run:

bash
ansible-playbook -i inventory.ini playbook.yml

Features
Idempotent Apache setup

SELinux context enforcement

Firewalld configuration

Security Notes
Do NOT commit sensitive data (e.g., passwords, real IPs).

Use SSH keys for authentication.

