                                                            #Criação de Nodes usando Kind#

Este repositório contém um arquivo de configuração YAML para criar um cluster Kubernetes usando Kind (Kubernetes IN Docker). 
O cluster criado consistirá em um nó de plano de controle e dois nós de trabalho.

Pré-requisitos
- Docker e Kind instalados.

Execute o comando a baixo para criar o cluster Kubernetes:

  kind create cluster --config kind-config.yaml

Isso criará um cluster Kubernetes com um nó de plano de controle e dois nós de trabalho, conforme especificado no arquivo kind-config.yaml.

Poderá verificar com o comando:

  kubectl get nodes
