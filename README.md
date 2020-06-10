# openshift_config_automation

DEPLOYS:

## cleaning operator: operator maintained by nlaaziz
ansible-playbook configure-cluster.yaml -e "config=CleaningOperator"

https://github.com/nlaaziz/cleaning-operator
https://hub.docker.com/repository/docker/nlaaziz/cleaning-operator/


## namespace config operator
ansible-playbook configure-cluster.yaml -e "config=NamespaceConfig"

## All
ansible-playbook configure-cluster.yaml -e "config=all"
