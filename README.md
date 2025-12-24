# docker-fundamentals

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

Este repositório é um guia prático de estudos sobre Docker, cobrindo desde a criação de containers simples até a orquestração e automação de ambientes.

🔗 **Quick access:** [🇧🇷 Português](#-português) | [🇺🇸 English](#-english)

---

## 🇧🇷 Português

### 📚 Sobre o Projeto
Este repositório contém anotações, exemplos de comandos e projetos práticos desenvolvidos durante o curso de Docker. O foco é entender como os containers facilitam o desenvolvimento e o deploy de aplicações.

### 🧠 Conteúdo
- **Introdução ao Docker:** O que são containers e por que utilizá-los.
- **Conceitos Fundamentais:** Gerenciamento de Imagens, Containers e Volumes.
- **Dockerfile:** Automação na criação de imagens personalizadas.
- **Docker Compose:** Orquestração de múltiplos containers e redes.
- **Persistência de Dados:** Uso de Volumes e Bind Mounts.

### 📦 Requisitos
Para rodar os exemplos, você precisará ter o Docker instalado:  
🔗 [Documentação de Instalação](https://docs.docker.com/get-docker/)

### 🚀 Exemplo de Execução
Para iniciar um servidor Nginx básico em segundo plano:
```bash
docker run -d -p 8080:80 nginx
```

## 🇺🇸 English

### 📚 About the Project
This repository contains notes, command examples, and practical projects developed during the Docker course. The main goal is to understand how containers simplify application development and deployment.

### 🧠 Content
- **Introduction to Docker:** What containers are and why to use them.
- **Core Concepts:** Image, container, and volume management.
- **Dockerfile:** Automation for creating custom images.
- **Docker Compose:** Orchestration of multiple containers and networks.
- **Data Persistence:** Using volumes and bind mounts.

### 📦 Requirements
To run the examples, Docker must be installed:
🔗 [Documentação de Instalação](https://docs.docker.com/get-docker/)

### 🚀 Quick Run
To start a basic Nginx server in background mode:

```bash
docker run -d -p 8080:80 nginx
```
