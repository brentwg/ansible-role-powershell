# Ansible Role: PowerShell
[![Build Status](https://travis-ci.org/brentwg/ansible-role-powershell.svg?branch=master)](https://travis-ci.org/brentwg/ansible-role-powershell)

Ansible role that installs PowerShell on Linux.  

## Requirements  

None.  

## Role Variables  

User modifiable variables and defaults are listed below. (For all variables, see `defaults/main.yml`):  
```
powershell_package_name: "powershell"
```  
The name of Visual Studio Code application package. (You know, in case it ever changes...)  
```
powershell_repo_key_url: "https://packages.microsoft.com/keys/microsoft.asc"
```
The URL that leads to Microsoft's repo key.  

## Dependencies

None.

## Sample Playbook

```
- hosts: all
  
  roles:
    - brentwg.powershell
```  
