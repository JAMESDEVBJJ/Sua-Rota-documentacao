# 🗺️ Sua Rota — Documentação do Sistema 

> **Projeto de Modelagem de Software / PMI II**  
> Documentação técnica, Especificação de Requisitos de Software (ERS) e Diagramas UML do sistema **Sua Rota** — plataforma colaborativa de mapeamento e percepção urbana.

---

## 📌 Sobre o Projeto

O **Sua Rota** é um sistema voltado para o mapeamento e análise colaborativa de locais urbanos sob diferentes perspectivas de vivência (moradores, estudantes, comerciantes, pesquisadores e visitantes). A plataforma permite registrar avaliações por critérios (como segurança, iluminação e limpeza), compartilhar memórias/relatos com fotos, comentar e denunciar conteúdos impróprios, auxiliando na construção de um mapa coletivo de percepção urbana.

---

## 🛠️ Stack e Decisões Arquiteturais

| Camada / Serviço | Tecnologia / Solução |
| :--- | :--- |
| **Front-end** | React + TypeScript (SPA) |
| **Biblioteca de Mapas** | Leaflet + OpenStreetMap |
| **Back-end** | C# ASP.NET Core (API REST / OpenAPI) |
| **Banco de Dados** | PostgreSQL |
| **Armazenamento de Mídia** | Object Storage (compatível com S3) |
| **Serviço de E-mail** | Resend / Serviço de E-mail Transacional |

---

## 📐 Artefatos e Diagramas UML

Todos os diagramas foram modelados utilizando a ferramenta [draw.io](https://app.diagrams.net/). Os arquivos editáveis (`.drawio`) e as versões exportadas (`.pdf` / `.png`)

---
## 📁 Estrutura de Documentação do Repositório

```text
SUA ROTA DOCUMENTAÇÃO/
│
├── 01-visao-geral/
│   ├── BMC-SuaRota.pdf               # Business Model Canvas do projeto
│   ├── necessidades-suaRota.pdf      # Mapeamento de problemas e necessidades
│   ├── Stakeholders-SuaRota.pdf      # Mapeamento de partes interessadas
│   └── Storytelling-SuaRota.pdf      # Narrativa do problema e solução
│
├── 02-requisitos/
│   ├── BMCEmRequisitosSuaRota.pdf    # Matriz BMC traduzida em requisitos
│   └── User-Stories-SuaRota.pdf      # Histórias de Usuário e Critérios de Aceite
│
├── 03-modelagem-uml/
│   └── SuaRota_N2_Diagramas_UML.pdf  # Conjunto completo de diagramas UML da N2
│
├── 04-planejamento-agil/
│   └── trelloQUadro.png              # Quadro de acompanhamento das Sprints/Tarefas
│
└── 05-prototipo/
    └── (Imagens e assets de base do design do sistema)
```

---

## 📄 Guias e Links Rápidos dos Artefatos

### 1. Visão Geral do Negócio (`01-visao-geral/`)
* 📊 [Business Model Canvas (BMC)](./01-visao-geral/BMC-SuaRota.pdf)
* 💡 [Levantamento de Necessidades](./01-visao-geral/necessidades-suaRota.pdf)
* 👥 [Mapeamento de Stakeholders](./01-visao-geral/Stakeholders-SuaRota.pdf)
* 📖 [Storytelling do Projeto](./01-visao-geral/Storytelling-SuaRota.pdf)

### 2. Engenharia de Requisitos (`02-requisitos/`)
* 📋 [BMC em Requisitos](./02-requisitos/BMCEmRequisitosSuaRota.pdf)
* 📝 [User Stories (Histórias de Usuário)](./02-requisitos/User-Stories-SuaRota.pdf)

### 3. Modelagem UML (`03-modelagem-uml/`)
* 📐 [Documento Único de Diagramas UML (N2)](./03-modelagem-uml/SuaRota_N2_Diagramas_UML.pdf)
  * *Contém: Casos de Uso, Classes de Domínio, Sequência, Atividades, Componentes e Execução/Implantação.*

### 4. Planejamento e Design (`04-planejamento-agil/` e `05-prototipo/`)
* 📌 [Quadro Kanban / Trello](./04-planejamento-agil/trelloQuadro.png)
* 🎨 [Imagens e Telas do Protótipo](./05-prototipo/)

---

## 🛠️ Resumo da Stack e Arquitetura

| Camada / Serviço | Tecnologia Escolhida |
| :--- | :--- |
| **Front-end** | React + TypeScript (SPA) |
| **Biblioteca de Mapas** | Leaflet + OpenStreetMap |
| **Back-end** | C# ASP.NET Core (API REST / OpenAPI) |
| **Banco de Dados** | PostgreSQL |
| **Armazenamento de Fotos** | Object Storage (compatível com S3) |
| **Serviço de E-mail** | Resend / Serviço de E-mail Transacional |

---

## 👥 Integrantes do Grupo

* **James Daniel Xavier**
