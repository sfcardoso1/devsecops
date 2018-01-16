#Ansible Role: Compliance/Hardening

Simple ansible role to harden linux systems and set few configuration.

## Example Playbook

 Here is a simple example playbook to use this role:

 ---
 - name: Playbook Compliance/Hardening
 - hosts: linux
  roles:
    - compliance


## Create password hash

openssl passwd -1 @MyPass
