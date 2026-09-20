# Requisitos do Sistema — Plataforma de Estudo Colaborativa

## 1. Objetivo
O sistema tem como objetivo oferecer uma plataforma de estudo onde alunos
possam consultar materiais elaborados por colegas de turma ou veteranos,
servindo como alternativa a quem não pode comparecer aos atendimentos
acadêmicos presenciais.

## 2. Perfis de usuário
- **Aluno criador**: cadastra materiais de estudo.
- **Aluno consumidor**: consulta e busca materiais cadastrados.
  (o mesmo usuário pode assumir os dois papéis)

## 3. Requisitos Funcionais
- RF01 — O sistema deve permitir o cadastro de usuários (nome, e-mail, senha, turma).
- RF02 — O sistema deve permitir login de usuários cadastrados.
- RF03 — O sistema deve permitir o cadastro de um material de estudo
  (título, disciplina, tipo, descrição, autor, arquivo/link).
- RF04 — O sistema deve permitir listar materiais filtrando por disciplina.
- RF05 — O sistema deve permitir buscar materiais por título ou autor.
- RF06 (opcional) — O sistema deve permitir que usuários avaliem materiais.

## 4. Requisitos Não Funcionais
- RNF01 — O sistema deve ser desenvolvido em Java.
- RNF02 — O sistema deve utilizar um banco de dados relacional (MySQL ou SQLite) via JDBC.
- RNF03 — A interface deve ser desktop, desenvolvida em Swing.
- RNF04 — O código deve seguir separação em camadas (Model, DAO, Service, View).
