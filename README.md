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

## Tecnologias Utilizadas
* **Front-end:** HTML5, CSS3 e JavaScript.
* **Back-end e API:** Google Apps Script (GAS).
* **Persistência de Dados:** Google Sheets.

## Estrutura do Projeto e Documentação
A documentação técnica e os artefatos de planejamento encontram-se no diretório `/docs`, incluindo Especificação de Requisitos, Dicionário de Dados e Casos de Uso.

## Diretrizes para Colaboradores
Para compreender o fluxo de submissão de código e criação de Issues, consulte o documento `CONTRIBUTING.md`.
