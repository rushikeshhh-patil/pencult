# RealmRover

RealmRover is a PowerShell script designed for Active Directory enumeration and information gathering. It provides a set of options to retrieve details about users, groups, computers, and users with Service Principal Names (SPNs) within the domain.

## Features

- **User Enumeration**: Enumerate all users in the domain and save the list to `domain-users.txt`.
- **Group Enumeration**: Enumerate all groups in the domain and save the list to `domain-groups.txt`.
- **Computer Enumeration**: Enumerate all computers in the domain and save the list to `domain-computers.txt`.
- **SPN User Enumeration**: Enumerate users with SPNs and save the list to `user-spn-list.txt`.

## Usage
```bash
.\RealmRover.ps1 -Option <1, 2, 3, 4>
```
## Options:
1: Enumerate all users in the domain and save to domain-users.txt.
2: Enumerate all groups in the domain and save them to domain-groups.txt.
3: Enumerate computers in the domain and save to domain-computers.txt.
4: Enumerate users with SPNs and save to user-spn-list.txt.
   
