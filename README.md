# dockernodes-ansible



A ansible script to installs docker nodes on CentOS 7

## Features
* deploy docker-ce nodes (latest 18.03 or after)
* add yum tools for installing docker-ce
* add repository for docker-ce installation


## Requirements

* ansible 2.4


## Example

modify inventories, then

```
ansible-playbook -i inventories/dev/hosts deploy-docker-nodes.yml
```

