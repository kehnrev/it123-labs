# IT 123 – Lab Report 2: Linux User and Group Management

**Student Name:** [KEHN REBADAVIA]  
**Date:** [8/21/2026]

---

## 1. Objectives

- Successfully create, configure, and manage user accounts and groups in Ubuntu Server.
- Implement strict directory permissions and ownership configurations to enforce Role-Based Access Control (RBAC).
- Verify security boundaries through multi-user testing.

---

## 2. Implementation Steps

### User and Group Configuration

Executed the following commands to provision users and groups:

```bash
adduser faculty2
adduser student4
groupadd facultygrp
groupadd studentgrp
usermod -aG facultygrp faculty2
usermod -aG studentgrp student4
```
