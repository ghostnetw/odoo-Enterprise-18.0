# 🚀 Odoo 18 Enterprise Deployment

![Odoo Version](https://img.shields.io/badge/Odoo-18.0%20Enterprise-purple)
![License](https://img.shields.io/badge/license-Proprietary-red)
![Platform](https://img.shields.io/badge/platform-Ubuntu%2022.04-blue)

This repository provides a ready-to-use deployment setup for **Odoo 18 Enterprise**, ideal for production environments. It includes best practices for installation, configuration, and customization on Ubuntu servers.

---

## 📦 Features

- ✅ Odoo 18.0 Enterprise edition
- ✅ PostgreSQL optimized setup
- ✅ Nginx reverse proxy with SSL (Let's Encrypt)
- ✅ Supervisor for process control
- ✅ Daily backups (optional)
- ✅ Clean folder structure
- ✅ Ready for multi-database instances

---

## 🧰 Requirements

- Ubuntu 22.04 LTS (recommended)
- Domain name (for SSL)
- Odoo 18 Enterprise code (you must have an official license)
- Root or sudo access

---------------------------------------------------

## ⚙️ Installation

```bash
# Clone the repo
git clone https://github.com/ghotnetw/odoo18-enterprise-18.0.git
cd odoo18-enterprise-deployment

# Run setup script (customize if needed)
chmod +x deploy.sh
./deploy.sh


