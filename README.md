                                                            #Criação de Nodes usando Kind#

Este repositório contém um arquivo de configuração YAML para criar um cluster Kubernetes usando Kind (Kubernetes IN Docker). 
O cluster criado consistirá em 1 Control Plane e 2 WorkerNodes.

Pré-requisitos
- Docker e Kind instalados.

Execute o comando a baixo para criar o cluster Kubernetes:

  kind create cluster --config kind-config.yaml

Isso criará um cluster Kubernetes com um Control Plane e dois WorkerNodes, conforme especificado no arquivo kind-config.yaml.

Poderá verificar com o comando:

  kubectl get nodes
