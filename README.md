# Linux Web Server Deployment

## Overview

This project demonstrates the deployment and administration of a Linux web server using Debian GNU/Linux and Nginx.

The server was configured in a VMware virtual machine and includes a custom website, Nginx server configuration, firewall rules, HTTPS/TLS, and basic troubleshooting.

## Environment

- Debian GNU/Linux 13
- VMware
- Nginx
- Bash
- systemd
- UFW
- OpenSSL
- Git/GitHub

## Tasks Completed

- Installed and verified Nginx
- Created a custom HTML website
- Configured an Nginx server block
- Managed Nginx with systemd
- Configured UFW firewall rules
- Allowed SSH, HTTP, and HTTPS traffic
- Created a self-signed TLS certificate
- Configured HTTPS in Nginx
- Tested HTTP and HTTPS connectivity
- Verified listening network ports
- Documented the deployment process

## Commands Used

```bash
sudo nginx -v
sudo systemctl status nginx
sudo systemctl restart nginx
sudo systemctl reload nginx
sudo nginx -t
sudo ufw status
sudo ufw allow ssh
sudo ufw allow 80/tcp
sudo ufw allow 443/tcp
sudo ss -tulpn
curl http://localhost
curl -k https://localhost

