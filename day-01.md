# 🖥️ IT Infrastructure — Quick Reference

A concise guide to essential IT infrastructure concepts.

---

### 🔐 Kerberos — Authentication
- Authenticates users and services using tickets.
- Commonly used in Active Directory for Single Sign-On (SSO).

> **Kerberos = "Who are you?"**

### 📂 LDAP — Directory Access
- Queries directory services such as Active Directory.
- Retrieves users, groups, computers, and their attributes.

> **LDAP = "What information does the directory have?"**

### ⚙️ GPO — Group Policy Object
- A collection of settings applied to users and computers.
- Centrally manages security policies and Windows configurations.

> **GPO = "What settings should be applied?"**

### 🗄️ File Server — File Sharing
- Stores and shares files across a network.
- Controls access through permissions.

> **File Server = "Where can users access shared files?"**

**Example:** Windows Server + Shared Folders

### 💾 NAS — Network Attached Storage
- Dedicated network storage for centralized file access.
- Often supports SMB/NFS, backups, and RAID.
- Can function as a File Server.

> **NAS = "Network storage that can also share files."**

**Example:** Synology NAS

---

## 📊 Quick Comparison

| Technology | Primary Function |
|------------|------------------|
| **Kerberos** | Authentication |
| **LDAP** | Directory queries |
| **GPO** | Centralized policy management |
| **File Server** | Network file sharing |
| **NAS** | Network storage and file services |

---

### 💡 Key Difference

**File Server** = A system that provides shared files.

**NAS** = A dedicated storage device that can act as a File Server.

*Not every File Server is a NAS.*
