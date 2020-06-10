# openshift_config_automation

DEPLOYS:

## namespace config operator
ansible-playbook configure-cluster.yaml -e "config=NamespaceConfig"

## cleaning operator
ansible-playbook configure-cluster.yaml -e "config=CleaningOperator"

## All
ansible-playbook configure-cluster.yaml -e "config=all"
