# Smartcard
## Requirements
* Ansible 2.8
* Red Hat/CentOS 8
* Red Hat/CentOS 7

## Role Description
* Configures Red Hat family systems to read smart cards.
* Installs tools for interacting with smart cards.

## Role Variables
|Name|Default Value|Description|
|---|---|---|
|`sc_cac_enabled`|no|Enables support for reading DoD Common Access Cards (CAC).|
|`sc_cackey_version`|0.7.5|The version of `cackey` to install.|

## Example Playbook
```
- hosts: localhost
  roles:
    - smartcard
```
