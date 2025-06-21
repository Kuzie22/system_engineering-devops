# Shell Permissions and User Management Project

This repository contains shell scripts that demonstrate basic Linux file permissions management, user switching, ownership changing, and permission modification commands.

## Directory

`0x01-shell_permissions`

## Scripts Overview

### 0-iam_betty
Switches the current user to the user `betty`.

---

### 1-who_am_i
Prints the effective username of the current user.

---

### 2-groups
Prints all the groups the current user is part of.

---

### 3-new_owner
Changes the owner of the file `hello` to the user `betty`.

---

### 4-empty
Creates an empty file named `hello`.

---

### 5-execute
Adds execute permission to the owner of the file `hello`.

---

### 6-multiple_permissions
Adds execute permission to the owner, read permission to the group, and no permissions to others on the file `hello`.

---

### 7-everybody
Adds execute permission to the owner, the group, and others on the file `hello`.

---

### 8-James_Bond
Sets the permission of the file `hello` as follows: owner can read and write; group can read; others have no permissions.

---

### 9-John_Doe
Sets the permission of the file `hello` as follows: owner can read and write; group has no permissions; others can read.

---

### 10-mirror_permissions
Sets the permissions of the file `hello` to be the same as those of the file `olleh`.

---

## How to Run

Make sure the scripts are executable:

```bash
chmod +x <script_name>
