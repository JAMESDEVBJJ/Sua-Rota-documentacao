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

## 📁 Estrutura do Repositório

```text
.
├── docs/
│   └── ERS_Sua_Rota_v2.0.pdf      # Especificação de Requisitos de Software completa
├── diagramas/
│   ├── editable/                  # Arquivos fontes editáveis (.drawio)
│   │   └── SuaRota_N2_Diagramas.drawio
│   └── exports/                   # Arquivos exportados em alta resolução (.pdf / .png)
│       ├── 01-casos-de-uso.pdf
│       ├── 02-classes-dominio.pdf
│       ├── 05-sequencia.pdf
│       ├── 07-atividades.pdf
│       ├── 08-componentes.pdf
│       └── 09-execucao.pdf
└── README.md                      # Apresentação do repositório
```

---

## 📄 Requisitos Rastreados (Resumo)

- **RF-001 a RF-004**: Gestão de contas, autenticação e perfil de vivência.
- **RF-005 a RF-011**: Visualização de mapas, busca de locais, avaliações por critério e mapa de calor.
- **RF-012 a RF-014**: Interações sociais (comentários, votos de utilidade e relatos/memórias com foto).
- **RF-015 a RF-016**: Sistema de denúncias e fila de moderação.
- **RN-001 a RN-013**: Regras de negócio de acesso, uniciadade de avaliações, moderação e verificação de conteúdos vedados.

---

## 👥 Integrantes do Grupo

- **Nome do Aluno 1** - *Papel / Responsabilidade no Projeto*
- **Nome do Aluno 2** - *Papel / Responsabilidade no Projeto*
- **Nome do Aluno 3** - *Papel / Responsabilidade no Projeto*
- **Nome do Aluno 4** - *Papel / Responsabilidade no Projeto*

---

> *Projeto desenvolvido para a disciplina de Projeto de Modelagem de Informação / Engenharia de Software.*
