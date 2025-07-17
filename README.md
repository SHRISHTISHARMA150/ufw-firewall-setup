# 🔥 Basic Firewall Configuration using UFW

## 🎯 Objective
Set up a basic firewall using UFW (Uncomplicated Firewall) on a Linux system.

## 🛠️ Tools Used
- Linux (Kali/Ubuntu)
- UFW (Uncomplicated Firewall)

## ⚙️ Steps Performed

1. Installed UFW using:
  sudo apt install ufw

2.Allowed SSH (port 22):
  sudo ufw allow ssh

3.Denied HTTP (port 80):
  sudo ufw deny http

4.Enabled UFW and checked rules:
  sudo ufw enable
  sudo ufw status verbose
  
✅ Result
SSH is allowed.

HTTP is denied.

Firewall is active and working.
