# 12: Kubernetes Fundamentals ☸️

Neste laboratório, usei uma cópia local do site **Rústicos Diniz** para praticar Docker e Kubernetes. A ideia foi aproveitar um projeto real que eu já conhecia para aprender como executar uma aplicação em containers.

🌐 **Site original:** [https://rusticosdiniz.com.br](https://rusticosdiniz.com.br)

## 💻 Sobre o projeto

Criei o site da Rústicos Diniz como presente para meus sogros. Ele continua publicado normalmente, sem Docker ou Kubernetes.

Para este laboratório, copiei os arquivos do site para o VS Code e usei essa cópia apenas para estudar. Assim, pude testar as ferramentas sem mexer no site original.

## 🐳 O que pratiquei com Docker

- Criação de uma imagem para executar o site com Nginx.
- Configuração do container para executar sem root.
- Execução local da aplicação.
- Verificação do funcionamento do site no navegador.

## ☸️ O que pratiquei com Kubernetes

- Criação de um cluster local com Kind.
- Criação de um Deployment e de um Service.
- Execução de duas réplicas da aplicação.
- Uso do `kubectl port-forward` para acessar o site no navegador.
- Exclusão de um Pod para observar o Kubernetes criando outro automaticamente.
- Alteração da quantidade de réplicas.
- Testes e correção de problemas durante a configuração.

## 🗂️ Estrutura do laboratório

```text
12-kubernetes-fundamentals/
├── Dockerfile
├── nginx.conf
├── .dockerignore
├── .gitignore
├── k8s/
│   ├── deployment.yaml
│   └── service.yaml
├── docs/
│   └── img/
│       ├── site-navegador.png
│       ├── arquivos-vscode.png
│       ├── cluster-kubernetes.png
│       ├── recuperacao-pod.png
│       └── escalonamento.png
└── README.md
```

Os arquivos do site e as imagens foram mantidos fora dos arquivos versionados deste laboratório para evitar duplicar o conteúdo original no GitHub.

## 📸 Registros do laboratório

### Site aberto no navegador

![Site Rústicos Diniz no navegador](docs/img/site-navegador.png)

### Arquivos no VS Code

![Arquivos do laboratório no VS Code](docs/img/arquivos-vscode.png)

### Cluster e aplicação em execução

![Cluster Kubernetes e aplicação em execução](docs/img/cluster-kubernetes.png)

### Teste de recuperação de Pod

![Teste de recuperação de Pod](docs/img/recuperacao-pod.png)

### Teste de escalonamento

![Teste de escalonamento da aplicação](docs/img/escalonamento.png)

## 📚 O que aprendi

Esse laboratório me ajudou a entender melhor como Docker e Kubernetes trabalham juntos. Também consegui visualizar, na prática, como o Kubernetes mantém a quantidade desejada de Pods e como posso acessar uma aplicação dentro de um cluster local.

Durante os testes, precisei resolver alguns problemas de configuração e entender melhor como as imagens Docker são disponibilizadas para o Kind.

Foi uma forma de estudar usando um projeto que já fazia parte da minha história, sem alterar o site que está no ar.

---

[⬅️ Voltar ao README principal](../README.md)
