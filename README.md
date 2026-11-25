# ☸️ Kubernetes Labs

Laboratórios práticos de **Kubernetes** da minha jornada de transição para **DevOps e Cloud**. Cada laboratório é feito na prática, com comandos reais, evidências (screenshots) e os problemas que encontrei pelo caminho.

> 👋 Sou a **Nicole Chagas**, estudante de Engenharia de Software em transição de carreira para DevOps/Cloud. Este repositório faz parte do meu portfólio técnico.

## 🧭 Trilha de estudos

Os laboratórios seguem uma numeração contínua entre os repositórios:

| Repositório | Laboratórios | Tema |
|-------------|--------------|------|
| [linux-labs](https://github.com/nicolejsdev/linux-labs) | 01 a 07 | Linux: fundamentos, usuários e permissões, processos, serviços, storage, redes e Bash |
| [docker-labs](https://github.com/nicolejsdev/docker-labs) | 08 a 11 | Docker: fundamentos, imagens, Compose e volumes |
| **kubernetes-labs** (este repositório) | 12 em diante | Kubernetes: Deployments, Services, escalonamento e autorrecuperação |

## 📚 Laboratórios deste repositório

| # | Laboratório | O que foi praticado | Tecnologias |
|---|-------------|---------------------|-------------|
| 12 | [Kubernetes Fundamentals](./12-kubernetes-fundamentals) | Imagem Nginx sem root, cluster local, Deployment, Service, `port-forward`, autorrecuperação e escalonamento | Docker, Nginx, Kind, kubectl, YAML |

Novos laboratórios serão adicionados a esta tabela conforme eu avançar nos estudos.

## ⭐ Projeto principal: Node.js CI/CD com Kubernetes

Meu projeto mais completo em Kubernetes vive em um **repositório próprio**, por ser uma aplicação com pipeline completo e não apenas um laboratório de estudo:

👉 **[nodejs-cicd-kubernetes](https://github.com/nicolejsdev/nodejs-cicd-kubernetes)**

- Aplicação **Node.js** com pipeline de **CI/CD no GitHub Actions**
- Scan de vulnerabilidades com **Trivy**, que **bloqueia o deploy** quando encontra problemas
- **Dockerfile multi-stage** e container **não-root**
- Deploy em cluster **Kind** por meio de um **runner self-hosted**

Se você quer ver como eu junto Docker, Kubernetes e automação em um fluxo único, comece por ele.

## 🛠️ Ferramentas utilizadas

- **Sistema operacional:** Ubuntu (Linux)
- **Containers:** Docker Engine
- **Kubernetes local:** Kind
- **CLI:** kubectl e Kustomize
- **Editor:** VS Code

As versões exatas de cada ferramenta ficam registradas no README de cada laboratório.

## 🗂️ Estrutura do repositório

```text
kubernetes-labs/
├── 12-kubernetes-fundamentals/   # Docker + Kind + Deployment + Service
└── README.md                     # este arquivo
```

Cada laboratório é autocontido e traz seu próprio `README.md` com objetivo, arquitetura, passo a passo, troubleshooting e aprendizados.

## 🎯 Objetivo

Construir uma base sólida e comprovada em Linux, containers e orquestração, com foco em vagas de **estágio ou júnior** em **DevOps, Cloud, infraestrutura e automação**.

## 📫 Contato

- 💼 [LinkedIn](https://www.linkedin.com/in/nicole-chagas-a30a08259/)
- 🐙 [GitHub](https://github.com/nicolejsdev)
