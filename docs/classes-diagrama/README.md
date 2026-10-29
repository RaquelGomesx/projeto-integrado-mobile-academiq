# Diagrama de Classes — AcademiQ

## 1. Objetivo

Este documento registra a organização das principais classes do sistema AcademiQ, uma aplicação de gestão acadêmica para o Ensino Fundamental e o Ensino Médio.

## 2. Principais entidades

- CadastroUsuario: armazena os dados necessários para o cadastro de usuários.
- Login: representa as informações utilizadas no processo de autenticação.
- Usuario: representa os usuários do sistema e seus respectivos perfis.
- Aluno: armazena os dados dos estudantes.
- Disciplina: representa as disciplinas oferecidas pela instituição.
- Atividade: representa as atividades acadêmicas disponibilizadas aos alunos.
- AlunoDisciplina: relaciona alunos e disciplinas.
- Notificacao: representa as notificações enviadas pelo sistema.
- Dispositivo: registra os dispositivos associados ao recebimento de notificações.

## 3. Relacionamentos

Os relacionamentos entre as entidades deverão representar as associações entre usuários, alunos, disciplinas, atividades e notificações, conforme as regras de negócio definidas para o AcademiQ.

A entidade AlunoDisciplina representa a associação entre alunos e disciplinas.

## 4. Observação

Este documento apresenta uma descrição inicial das entidades. O diagrama UML definitivo deverá ser validado de acordo com o modelo de dados e os requisitos do projeto.

## 5. Finalidade

Documentar a estrutura conceitual do sistema e facilitar o entendimento da equipe durante o desenvolvimento do AcademiQ.
