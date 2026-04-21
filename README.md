# 🚀 Projeto SRE & DevOps com Kubernetes

Repositório criado para acompanhar a evolução prática dos estudos em **SRE, DevOps e Kubernetes**, com foco em hands-on e simulação de cenários reais de infraestrutura.

---

## 🎯 Objetivo

Este projeto tem como objetivo desenvolver, na prática, conhecimentos essenciais em:

* Versionamento de código (Git/GitHub)
* Containerização com Docker
* Orquestração com Kubernetes
* Deploy de aplicações
* Observabilidade e troubleshooting

---

## 📚 Estrutura dos Desafios

O repositório está organizado por desafios progressivos, cada um abordando um conceito importante da stack DevOps.

---

### 🔹 Desafio 1 — Configuração de Ambiente e Primeiro Projeto

**Objetivo:**
Configurar o ambiente de desenvolvimento e realizar o primeiro versionamento.

**Principais atividades:**

* Criação do repositório no GitHub
* Configuração do Git local
* Implementação de um `Hello World` em Python
* Documentação inicial do projeto
* Criação de conta no Docker Hub

---

### 🔹 Desafio 2 — Preparação de Ambiente Kubernetes

**Objetivo:**
Preparar o ambiente local para trabalhar com Kubernetes.

**Principais atividades:**

* Instalação do Docker
* Criação de cluster local (Kind, k3d ou Minikube)
* Instalação do `kubectl`
* Instalação do `kubectx` e `kubens`
* Criação de namespace (não default)

---

### 🔹 Desafio 3 — Primeiro Deploy no Kubernetes

**Objetivo:**
Realizar o deploy de uma aplicação no cluster Kubernetes.

**Principais atividades:**

* Containerização da aplicação (`Dockerfile`)
* Publicação da imagem no Docker Hub
* Criação de Deployment
* Criação de Service (NodePort)
* Escalabilidade (Scaling)
* Auto recuperação (Auto Healing)

---

### 🔹 Desafio 4 — Arquitetura e Troubleshooting no Kubernetes

**Objetivo:**
Compreender a arquitetura do Kubernetes e diagnosticar falhas.

**Principais atividades:**

* Análise dos nodes do cluster
* Exploração do Control Plane
* Investigação dos componentes (kubelet, kube-proxy, etc.)
* Entendimento do fluxo do `kubectl`
* Criação de cenário com erro proposital
* Diagnóstico e correção de falhas

---

## 🛠️ Tecnologias Utilizadas

* Python
* Docker
* Kubernetes
* kubectl
* kubectx / kubens
* Git & GitHub

---

## ▶️ Como executar o projeto (exemplo básico)

```bash
python3 hello.py
```

---

## 📦 Docker Hub

As imagens utilizadas no projeto são publicadas no Docker Hub:

👉 *(adicione aqui o seu link)*

---

## 📁 Organização do Repositório

```
.
├── desafio1/
├── desafio2/
├── desafio3/
├── desafio4/
└── README.md
```

---

## 📌 Observações

* Os desafios são incrementais e refletem evolução prática
* O foco está em aprendizado aplicado (hands-on)
* Cada etapa pode conter scripts, YAMLs e evidências de execução

---

## 🚀 Próximos passos

* Automatizar deploy com CI/CD
* Implementar observabilidade (Prometheus/Grafana)
* Trabalhar com ambientes cloud (AWS/Azure)

---

## 👩‍💻 Autora

Projeto desenvolvido como parte de estudos em SRE/DevOps.

---

✨ Em evolução constante
