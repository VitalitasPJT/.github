# Vitalitas

> **Plataforma Web e Mobile Integrada para Revolucionar a Gestão e a Experiência em Academias.**

![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow?style=for-the-badge)
![Contexto](https://img.shields.io/badge/Contexto-Acadêmico_UniCEUB-blue?style=for-the-badge)
![Licença](https://img.shields.io/badge/Licença-Direitos_Reservados-red?style=for-the-badge)

<div align="center">

![.NET](https://img.shields.io/badge/.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)

</div>

## Contexto Acadêmico

O **Vitalitas** é desenvolvido no âmbito da disciplina de **Projeto Integrador** do curso de Ciência da Computação do **Centro Universitário de Brasília (UniCEUB)**.

Esta iniciativa integra a proposta pedagógica da instituição, simulando um ambiente real de desenvolvimento de software com as seguintes características:

* **Orientação Docente:** Todo o ciclo de vida do projeto, da concepção à entrega, é supervisionado por professores especialistas.
* **Multidisciplinaridade:** A solução aplica conhecimentos de diversas áreas, incluindo:
    * *Engenharia de Software* (Processos e Requisitos)
    * *Banco de Dados* (Modelagem e SQL)
    * *Programação Web* (Frontend e Backend)
    * *Arquitetura de Sistemas* (Padrões e Cloud Computing)
* **Metodologia Ágil:** A equipe utiliza abordagens ágeis para planejamento, desenvolvimento incremental e validação contínua.

## Visão Geral do Projeto

### O Problema
Muitas academias ainda realizam a gestão de alunos, treinos e avaliações físicas através de processos manuais, planilhas desconexas ou ferramentas fragmentadas. Esse cenário resulta em:
* **Retrabalho operacional** e baixa eficiência administrativa.
* **Inconsistência de dados**, dificultando a tomada de decisão.
* **Experiência limitada** para o aluno, sem acompanhamento digital de sua evolução.

### A Solução Vitalitas
O **Vitalitas** propõe uma plataforma web unificada que centraliza as informações operacionais, administrativas e técnicas da academia.

A entrega de valor do projeto baseia-se em quatro pilares:
1.  **Centralização:** Dados de alunos, contratos, treinos e avaliações em um único lugar.
2.  **Eficiência:** Automação de tarefas repetitivas e controle de acesso hierárquico.
3.  **Confiabilidade:** Segurança da informação e integridade dos dados de saúde.
4.  **Escalabilidade:** Arquitetura em nuvem preparada para crescimento, com uma API robusta servindo simultaneamente o sistema web de gestão e o aplicativo mobile dos alunos.

## Escopo do Projeto (MVP)

O escopo atual foca no **Produto Mínimo Viável (MVP)**.
O objetivo é entregar um conjunto funcional que permita a operação básica da academia, validando a solução em ambiente real.

### Funcionalidades Previstas

O sistema cobre os fluxos críticos de operação:

* **Autenticação e Segurança**
    * Login seguro via JWT (JSON Web Tokens).
    * Controle de Acesso Baseado em Função (RBAC): Perfis distintos para **Administrador**, **Professor** e **Aluno**.
    * Fluxo de primeiro acesso com alteração obrigatória de senha.

* **Gestão Administrativa (Backoffice)**
    * Cadastro centralizado de usuários (Staff e Alunos).
    * Regras de negócio hierárquicas (ex: restrições de criação por perfil).
    * **Gestão de Saúde:** Criação e monitoramento obrigatório de fichas médicas.

* **Gestão Técnica e Treinos**
    * Criação e edição de fichas de treino personalizadas.
    * Histórico de evolução e comparação entre fichas anteriores.
    * Agendamento de avaliações físicas via calendário.

* **Plataformas de Acesso**
    * **Portal Web (Gestão e Professores):** Administração da academia, gestão de alunos vinculados e prescrição detalhada de treinos.
    * **App do Aluno (Mobile):** Aplicativo nativo dedicado para visualização da ficha de treinos em tempo real, acompanhamento de evolução, agenda e dados cadastrais.

### Funcionalidades Futuras (V2)

Para garantir a entrega dentro do prazo acadêmico, os seguintes itens estão planejados para versões futuras:

* Gamificação e Ranking por XP (Experiência).
* Integração financeira e pagamentos online.
* Funcionalidades avançadas de Inteligência Artificial para análise de treinos.
* Cadastro complexo de bioimpedância.

## Tecnologias e Repositórios

O projeto está dividido em dois repositórios principais, cada um focado em uma parte da solução.

### Frontend (Interface Web)
Responsável pela experiência do usuário, construído com foco em produtividade e tipagem estática.

* **Stack:** React, TypeScript, Bootstrap, Vite.
* **Bibliotecas:** Axios, React Router DOM, JWT-decode.
* **Repositório:** [vitalita/vitalitas-frontend](https://github.com/VitalitasPJT/vitalitas-frontend-app)

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=flat-square&logo=bootstrap&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

### Mobile (App do Aluno)
Aplicativo nativo construído para oferecer uma experiência fluida aos alunos durante os treinos, consumindo a mesma API do sistema web.

* **Stack:** React Native, TypeScript.
* **Bibliotecas:** Axios, React Navigation, JWT-decode.
* **Repositório:** [vitalita/vitalitas-frontend](https://github.com/VitalitasPJT/vitalitas-frontend-app)

![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)

### Backend (API & Dados)
Responsável pelas regras de negócio, segurança e persistência dos dados .

* **Stack:** .NET 8 (ASP.NET Core), C#.
* **Banco de Dados:** SQL Server 2022 Express.
* **Infraestrutura:** Microsoft Azure (App Service + SQL Database).
* **Segurança:** JWT (JSON Web Tokens).
* **Repositório:** [vitalita/vitalitas-backend](https://github.com/VitalitasPJT/vitalitas-backend)

![.NET](https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-Secure-000000?style=flat-square&logo=json-web-tokens&logoColor=white)

## Equipe de Desenvolvimento

A equipe do projeto **Vitalitas** possui papéis bem definidos para garantir a cobertura de todas as áreas da Engenharia de Software:

### Gestão e Liderança
* **Sanderson de Oliveira Machado** - *Gerente de Projeto / P.O. / Tech Lead*
    * **Atribuições:** Gerenciamento de escopo e cronograma, definição do backlog (Product Owner) e liderança da arquitetura Backend.
    * 📧 [sanderson.oliveira@sempreceub.com](mailto:sanderson.oliveira@sempreceub.com)
    * [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sandersonnexum) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/sandersonnexum)

* **Giovanna Couto Lacerda** - *Scrum Master / Analista de Requisitos*
    * **Atribuições:** Facilitação das cerimônias ágeis, remoção de impedimentos e documentação detalhada dos requisitos.
    * 📧 [giovanna.couto@sempreceub.com](mailto:giovanna.couto@sempreceub.com)
    * [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](LINK_DO_LINKEDIN) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](LINK_DO_GITHUB)

### Frontend & UX
* **Arthur Guarita Brasil** - *Tech Lead Front-end & Mobile / UX UI Designer*
    * **Atribuições:** Prototipação de telas, definição de UX e liderança técnica do desenvolvimento da interface.
    * 📧 [arthur.guarita@sempreceub.com](mailto:arthur.guarita@sempreceub.com)
    * [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arthur-guarit%C3%A1-brasil-09384b379/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/arthurguaritabrasil)

* **Iuri Guimarães Pinheiro** - *Desenvolvedor Front-End*
    * **Atribuições:** Implementação de componentes visuais, integração com a API e manutenção do código cliente.
    * 📧 [iuri.gp@sempreceub.com](mailto:iuri.gp@sempreceub.com)
    * [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/iuri-guimar%C3%A3es-pinheiro-97159b310/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/IuriGP)

### Backend & Dados
* **Hugo Ferreira Matos** - *DBA / QA (Quality Assurance)*
    * **Atribuições:** Modelagem de dados (DER-MER), criação de scripts SQL e execução de testes de qualidade para estabilidade do sistema.
    * 📧 [hugo.fmatos@sempreceub.com](mailto:hugo.fmatos@sempreceub.com)
    * [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](LINK_DO_LINKEDIN) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/HugoFMat)

* **Pedro Luiz Souza de Abreu** - *Desenvolvedor Back-end*
    * **Atribuições:** Desenvolvimento de APIs e serviços, implementação de regras de negócio e integração com banco de dados.
    * 📧 [pedro.la@sempreceub.com](mailto:pedro.la@sempreceub.com)
    * [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedro-luiz-abreu-90a849355/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/Pedrolsza)

## Licença

Este projeto foi desenvolvido exclusivamente para fins acadêmicos na disciplina de **Projeto Integrador** do **Centro Universitário de Brasília (UniCEUB)**.

Copyright © 2026 **Vitalitas**. Todos os direitos reservados.