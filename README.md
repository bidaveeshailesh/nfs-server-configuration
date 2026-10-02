# NFS Server Configuration on Linux

## 📌 Project Overview

This project demonstrates how to configure an **NFS (Network File System) server on Linux** to share directories between a server and client system over a network.

The project covers NFS installation, directory sharing, permissions, service management, client mounting, and testing.

## 🏗️ Project Architecture

```text id="7x3mqa"
             Network
                |
       +--------+--------+
       |                 |
       v                 v
 NFS Server          NFS Client
       |                 |
       | Exported        | Mounted
       | Directory       | Directory
       +--------+--------+
                |
          Shared Files
```

## 🐧 Technologies Used

- Linux
- NFS
- Shell Commands
- File Permissions
- System Services
- Git & GitHub

## ⚙️ Configuration Steps

1. Install the NFS server package.
2. Create a directory to share.
3. Configure the NFS export.
4. Set appropriate directory permissions.
5. Start and enable the NFS service.
6. Configure firewall rules if required.
7. Install the NFS client components.
8. Mount the shared directory on the client.
9. Test file creation and access between the server and client.

## 🔐 Security

Basic security considerations include:

- Restricting which clients can access the export
- Using appropriate file permissions
- Limiting network access with firewall rules
- Sharing only required directories
- Managing user and group permissions carefully

## 🎯 What I Learned

- Linux NFS fundamentals
- Server-client architecture
- Network file sharing
- Linux directory permissions
- Mounting remote file systems
- Linux service management
- Basic network troubleshooting
- Documenting Linux projects using GitHub

## 📂 Project Type

**Linux / Server Administration / NFS / Networking / DevOps**

## 👨‍💻 Author

**Shailesh Bidave**

GitHub: [@bidaveeshailesh](https://github.com/bidaveeshailesh)
