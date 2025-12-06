# Linux User & Permissions Management Lab

This project is a hands-on Linux administration lab focused on creating users, managing groups, and configuring file permissions to simulate a real multi-user server environment. It demonstrates core sysadmin and security skills such as role-based access control (RBAC), directory permissions, user provisioning, and access auditing.

---

## 🔧 Project Overview

In this lab, I created a directory structure and implemented access restrictions based on user roles. The goal is to simulate how real organizations manage access to finance, HR, and shared resources on a Linux server.

This project demonstrates:

- User account creation  
- Group creation and membership management  
- Secure directory permissions  
- Folder-level access control  
- Least-privilege enforcement  
- Permission troubleshooting  
- Testing access using multiple user accounts  

---

## 📂 Directory Structure

/projects/
├── shared/ # Accessible by all users
├── finance/ # Only finance group members
├── hr/ # Only HR group members
└── secret/ # Accessible only by root


---

## 🧠 Skills Demonstrated

### 🟦 Linux Administration
- Creating and managing users (`useradd`, `passwd`)
- Creating groups and assigning users to roles (`groupadd`, `usermod`)

### 🟩 Security & RBAC
- Implementing least privilege  
- Restricting access by folder ownership  
- Securing sensitive directories (chmod 700)

### 🟨 File Permissions
- Understanding rwx permissions  
- Using `chmod`, `chown`, and `ls -l`  
- Applying group-based permissions (770, 775)

### 🟥 Troubleshooting
- Access testing via `su - username`  
- Validating group membership (`groups`)  
- Reviewing permissions (`ls -l /projects`)

---

## 🛠️ Commands Used

### Create directories
```bash
sudo mkdir -p /projects/{shared,finance,hr,secret}

Create users

sudo useradd -m alice
sudo useradd -m derek
sudo useradd -m dontay
sudo useradd -m demetrius
sudo passwd username

Create groups

sudo groupadd finance
sudo groupadd hr

Assign users to groups

sudo usermod -aG finance alice
sudo usermod -aG finance bob
sudo usermod -aG hr charlie

Set directory ownership

sudo chown :finance /projects/finance
sudo chown :hr /projects/hr

Apply permissions

sudo chmod 770 /projects/finance
sudo chmod 770 /projects/hr
sudo chmod 775 /projects/shared
sudo chmod 700 /projects/secret

Test access

su - alice
su - derek
su - demetrius
su - dontay

🔍 What I Learned

Through this lab, I gained practical experience in:

    Managing Linux users/groups in a secure environment

    Enforcing real-world access policies

    Troubleshooting permission issues

    Understanding how multi-user systems work

    Practicing commands used daily by sysadmins & network engineers

This forms a foundation for more advanced skills such as:

    SSH user management

    File server configuration (Samba/NFS)

    Automation with Bash/Ansible

<img width="1854" height="1048" alt="Screenshot from 2025-11-29 21-27-01" src="https://github.com/user-attachments/assets/6d1d3172-a5b6-46df-a1fd-3d3d9c9afc0f" />


    Server hardening

    Enterprise authentication (LDAP, AD)
