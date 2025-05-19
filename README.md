# jenkins-installer
# Jenkins Installer Script

This repository provides an automated installation script to set up Jenkins on an Ubuntu/Debian-based system using a single command.

## 🚀 Features

- Installs **OpenJDK 17**
- Adds the official **Jenkins APT repository**
- Installs the latest **Jenkins LTS**
- Starts and enables the **Jenkins service**
- Opens **port 8080** on UFW if it's active
- Displays the **initial admin password**

## 🧰 Requirements

- Ubuntu/Debian-based system
- `curl` installed
- Root or sudo privileges
- Internet access

## 📥 Installation Steps

1. Connect to your server using **PuTTY** or any SSH client.
2. Download and run the script:

```bash
curl -O https://raw.githubusercontent.com/rutvik-3377/jenkins-installer/main/install_jenkins.sh

chmod +x install_jenkins.sh
./install_jenkins.sh
