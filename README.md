# Ansible Automation Project

This repository contains Ansible roles and playbooks I created for automating server setup, configuration, and deployment.  
It includes static and dynamic playbooks as well as role-based automation for managing various services.

## 📂 Project Structure

- **Roles**
  - apache
  - angular
  - html
- **Playbooks**
  - 01-single-play.yml  
  - 02-multi-play.yml  
  - 03-httpd.yml  
  - 04-nginx.yml  
  - 05-food.yml  
  - 06-maintenance.yml  
  - 07-ubuntu.yml  
  - 08-shell-platform.yml  
  - 09-static.yml  
  - 10-dynamic.yml  
  - 11-angular-app.yml  
  - 12-html-app.yml  
  - 13-php-app.yml  
  - 14-lamp-app.yml  
- **Inventories**
  - hosts.ini

## 🚀 Usage

Run playbooks with:

\`\`\`bash
ansible-playbook -i hosts.ini <playbook-name>.yml
\`\`\`

Example:

\`\`\`bash
ansible-playbook -i hosts.ini 03-httpd.yml
\`\`\`

## ✅ Notes
- Tested on AWS EC2 instances (Amazon Linux & Ubuntu).
- Includes both static and dynamic inventory examples.
- Naming conventions are unique to this repo.

---
