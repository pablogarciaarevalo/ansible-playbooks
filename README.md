# Ansible Playbooks

Hello-World Ansible playbooks for NetApp storage systems

### Prerequisites

* Ansible 2.3 or later

### Installation

```shell
$ git clone https://github.com/pablogarciaarevalo/ansible_playbooks.git
```

### Playbook for ONTAP

#### Requirements

* ONTAP 8.3 or later
* netapp-lib module

```shell
$ pip install netapp-lib --user
```

#### Running playbook
Example: Create a new Storage Virtual Machine

```shell
$ ansible-playbook example_netapp_ontap.yml
```

### Playbook for SolidFire

#### Requirements

* solidfire-sdk-python module

```shell
$ pip install solidfire-sdk-python
```

#### Running playbook
Example: Create a new volume

```shell
$ ansible-playbook example_netapp_solidfire.yml
```
