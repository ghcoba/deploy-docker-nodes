# deploy-docker-nodes using ansible



A ansible script to installs docker nodes on CentOS 7

## Features
* for centos 7
* deploy docker-ce nodes (latest 18.06 or after)
* add yum tools for installing docker-ce
* add repository for docker-ce installation


## Requirements

* ansible 2.4


## Example

modify inventories, then

```
ansible-playbook -i inventories/dev/hosts deploy-docker-nodes.yml
```

