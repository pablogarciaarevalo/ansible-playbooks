# Ansible Playbooks

Repository for my Ansible Playbooks

## Prerequisites

* ONTAP 8.3 or later
* Ansible 2.3 or later

## Installation

Depends on the storage system you are working with, a different module is needed.

#### ONTAP

```shell
$ pip install netapp-lib --user
```

#### SolidFire

```shell
$ pip install solidfire-sdk-python
```


And clone this repository:
```shell
$ git clone https://github.com/pablogarciaarevalo/ansible_playbooks.git
```

## Running playbooks

Modify the values according to your storage systems and run the playbook

#### Hello world playbook for ONTAP

```shell
$ ansible-playbook example_netapp_ontap.yml
```

#### Hello world playbook for SolidFire

```shell
$ ansible-playbook example_netapp_solidfire.yml
```
