# Day 06: User Creation and Management in Linux

## Overview
Linux is a multi-user operating system, which means multiple users can
access the system at the same time. User management commands are used
to create users, set passwords, assign groups, and manage permissions.

These commands are very important for system administration and
server management.

---

## Commands

### useradd
**Purpose:**  
Used to create a new user in the Linux system.

**Syntax:**
- useradd username

**Usage:**
- Creates a new user account
- Commonly used by system administrators

---

### passwd
**Purpose:**  
Used to set or change the password of a user.

**Syntax:**
- passwd username

**Usage:**
- Sets password for a new user
- Can also change an existing password

---

### userdel
**Purpose:**  
Used to delete a user from the system.

**Syntax:**
- userdel username

**Usage:**
- Removes user account
- Used when a user no longer needs access

---

### groupadd
**Purpose:**  
Used to create a new group.

**Syntax:**
- groupadd groupname

**Usage:**
- Helps manage multiple users together
- Useful for permission management

---

### groups
**Purpose:**  
Used to check which groups a user belongs to.

**Syntax:**
- groups username

**Usage:**
- Displays all groups assigned to a user

---

## Why These Commands Matter
- Manage multiple users on a system
- Improve system security
- Control access to files and resources
- Essential for server and enterprise environments

---

## Summary
- useradd → create a new user  
- passwd → set or change user password  
- userdel → delete a user  
- groupadd → create a new group  
- groups → check user group membership  

User management is a core responsibility of Linux system administrators.
