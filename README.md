## 📦 Kubernetes Initial Service
Este projeto tem como objetivo fornecer uma configuração inicial de serviços no Kubernetes, facilitando o bootstrap de aplicações e serviços essenciais em um cluster.

## 🚀 Objetivo
Automatizar a criação e configuração de serviços iniciais em um ambiente Kubernetes, como:
Deploys básicos
Services (ClusterIP, NodePort, LoadBalancer)
ConfigMaps e Secrets
Namespaces e RBAC

## 📁 Estrutura do Projeto
kubernetes-initial-service/
├── manifests/
│   ├── namespace.yaml
│   ├── service.yaml
│   ├── deployment.yaml
│   └── configmap.yaml
├── scripts/
│   └── apply.sh
└── README.md

## ⚙️ Pré-requisitos
Kubernetes 1.20+
kubectl configurado e autenticado com o cluster
Permissões para aplicar recursos no cluster

## 📦 Instalação
Shellgit clone https://github.com/vit0ur/kubernetes-initial-service.gitcd kubernetes-initial-service./scripts/apply.shShow more lines

## 📄 Recursos Criados
Namespace personalizado
Serviço exposto via ClusterIP
Deployment com imagem de exemplo
ConfigMap com variáveis de ambiente

## 🛠️ Personalização
Você pode editar os arquivos YAML em manifests/ para adaptar os recursos às necessidades do seu ambiente.

## 📚 Referências
Documentação oficial do Kubernetes
kubectl cheatsheet
