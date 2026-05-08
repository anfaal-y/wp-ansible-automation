# Ansible LAMP Stack Automation

This project automates the installation and configuration of a LAMP stack (Linux, Apache, MySQL, PHP) on remote Linux servers using Ansible playbooks.

## 🚀 Features

* Automated Apache installation and configuration
* MySQL server installation and setup
* PHP installation with required modules
* Service management using Ansible
* Idempotent automation for repeatable deployments

## 🛠 Technologies Used

* Ansible
* Linux (Ubuntu/CentOS)
* Apache
* MySQL
* PHP

## 📋 Prerequisites

* Ansible installed on control node
* SSH access to target servers
* Inventory file configured with target hosts

## ▶️ Usage

Clone the repository:

```bash id="gfmr1w"
git clone <repository-url>
cd ansible-lamp-automation
```

Run the playbook:

```bash id="s9t1ml"
ansible-playbook -i inventory.ini lamp.yml
```

## 📂 Project Structure

```text id="dgq70g"
├── inventory.ini
├── lamp.yml
├── roles/
│   ├── apache/
│   ├── mysql/
│   └── php/
└── README.md
```

## ✅ Outcome

Successfully automated the deployment and configuration of a complete LAMP stack environment using Ansible, reducing manual setup effort and improving deployment consistency.
