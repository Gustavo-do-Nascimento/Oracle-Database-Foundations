# DFo 1-2: Introdução ao Banco de Dados

## Exercício 1 — Considerações de Design do Banco de Dados

### Objetivo

Identificar e analisar quais informações precisam ser armazenadas em um banco de dados para atender às necessidades de diferentes sistemas, considerando os dados necessários para o cadastro de alunos e para o gerenciamento de uma biblioteca.

### Descrição da Atividade

A atividade consiste em analisar dois cenários de sistemas — um sistema de registro de alunos e um sistema de gerenciamento de biblioteca — e identificar os principais dados que devem ser armazenados em cada um deles. O exercício tem como finalidade desenvolver a compreensão sobre a identificação de informações necessárias para a estruturação de um banco de dados.

### Resolução

#### 1. Sistema de Registro de Alunos

Os principais dados que podem ser armazenados no banco de dados são:

- ID do aluno;
- Nome completo;
- Data de nascimento;
- CPF ou outro documento de identificação;
- Endereço;
- Telefone;
- E-mail;
- Data de matrícula;
- Curso ou série;
- Ano letivo;
- Status da matrícula;
- Disciplinas matriculadas;
- Notas;
- Frequência;
- Dados dos responsáveis, quando aplicável, como nome, parentesco, telefone e e-mail.

Esses dados permitem realizar o cadastro dos alunos, manter suas informações atualizadas e consultar informações acadêmicas e cadastrais.

#### 2. Sistema de Gerenciamento de Biblioteca

**Dados dos livros:**

- ID do livro;
- Título;
- ISBN;
- Autor;
- Editora;
- Ano de publicação;
- Categoria;
- Quantidade de exemplares;
- Localização;
- Disponibilidade.

**Dados dos clientes:**

- ID do cliente;
- Nome completo;
- CPF ou outro documento de identificação;
- Endereço;
- Telefone;
- E-mail;
- Data de cadastro;
- Status do cadastro.

**Dados das atividades da biblioteca:**

- ID do empréstimo;
- Livro relacionado;
- Cliente responsável pelo empréstimo;
- Data do empréstimo;
- Data prevista para devolução;
- Data efetiva de devolução;
- Status do empréstimo;
- Reservas de livros;
- Registro de atrasos e multas, quando aplicável.

Esses dados permitem controlar o acervo, os clientes e as principais operações realizadas diariamente, como empréstimos, devoluções, reservas e controle de atrasos.
