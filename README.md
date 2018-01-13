# Ansible Playbooks

Repository for my Ansible Playbooks

## Requirements

* ONTAP 8.3 or later
* Ansible 2.3 or later

## Installation

Install the below netapp-lib module

```shell
$ pip install netapp-lib --user
```

And clone this repository:
```shell
$ git clone https://github.com/pablogarciaarevalo/ansible_playbooks.git
```

## Run a Hello world for NetApp ONTAP

Modify the values according to your storage systems and run the playbook

```shell
$ ansible-playbook example_netapp_ontap.yml
```