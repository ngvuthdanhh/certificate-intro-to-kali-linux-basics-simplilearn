# 05 – Users and Permissions

## Overview
Understanding users, groups, and permissions is crucial for system security.

## Users
- `root` – Superuser with full privileges
- Regular users – Limited access

## Groups
- Used to manage multiple users with similar access rights
- Add user to group: `usermod -aG groupname username`

## Permissions
- Read (`r`), Write (`w`), Execute (`x`)
- View permissions: `ls -l`
- Change permissions: `chmod 755 filename`
- Change ownership: `chown user:group filename`
