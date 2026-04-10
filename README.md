#  Labsys

##  Sobre o Projeto
O **Labsys** é um sistema web projetado para facilitar o gerenciamento de tarefas e a manutenção do nosso laboratório. 

O objetivo principal é permitir que alunos sugiram demandas necessárias, enquanto administradores podem gerenciar, revisar e aprovar essas tarefas. Para incentivar o engajamento, o sistema conta com uma mecânica de **gamificação**, recompensando a conclusão de tarefas com pontos de experiência (XP).

##  Principais Funcionalidades

* **Autenticação Simplificada:** Login de alunos e admins via Google OAuth (usando e-mail, matrícula e username).
* **Gestão de Tarefas:** Criação de chamados detalhando a área (Eletrônica, Gestão, Modelagem, Impressão, etc.), tempo previsto, dificuldade e nível de urgência.
* **Painel Administrativo:** Área exclusiva para chefes de laboratório e monitores gerenciarem, deletarem ou aprovarem tarefas.
* **Gamificação e Progressão:** * Usuários ganham XP geral ao concluir atividades.
    * Sistema de especialização: ganho de XP específico por área (Ex: *Nível 5 em Eletrônica*, *Nível 3 em Modelagem 3D*).

##  Arquitetura do Sistema

O projeto adota uma arquitetura separada em módulos principais:

* **Frontend (Web App):** Interface do usuário onde os alunos visualizam seus perfis de XP e tarefas, e os admins acessam o painel de controle.
* **Backend (API):** Servidor responsável pelas regras de negócio, cálculo matemático de XP, sistema de permissões (Roles) e comunicação com o banco de dados.
* **Banco de Dados:** Armazenamento das entidades principais (`users`, `tasks`, `xp_log`, `areas`, `roles`).

##  Estrutura do Repositório

```text
labsys/
├── docs/                # Documentação do projeto
│   ├── requisitos.md    # Regras de negócio, roles, fluxos
│   ├── modelo-dados.md  # Entidades do banco e relacionamentos
│   └── wireframes/      # Imagens das telas planejadas
├── frontend/            # Código-fonte do site (Interface)
└── backend/             # Código-fonte da API e regras de servidor
