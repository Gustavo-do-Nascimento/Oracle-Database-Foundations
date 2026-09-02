# DFo 1-4: Requisitos de Negócios

## Exercício 1 — Requisitos de Negócios

## Objetivo

Identificar e analisar as regras de negócio presentes em diferentes cenários, relacionando cada regra às respectivas restrições que podem ser aplicadas ao banco de dados para garantir a integridade e a consistência das informações.

## Descrição da Atividade

A atividade consiste em analisar os cenários da biblioteca LibBook e do Hospital Star Care, identificar suas principais regras de negócio e relacioná-las às constraints necessárias para representá-las no banco de dados. O exercício busca desenvolver a capacidade de transformar requisitos de negócio em regras e restrições aplicáveis à estrutura de um banco de dados.

### 1. LibBook

| Regra de negócio | Constraint associada |
|---|---|
| A biblioteca deve possuir diferentes tipos de associação. | O tipo de associação deve ser definido a partir de valores previamente cadastrados. |
| Inicialmente, existem os tipos de associação Corporativa, Aluno e Individual. | O tipo de associação deve aceitar somente os tipos disponíveis no sistema. |
| A associação Aluno é gratuita. | A taxa da associação Aluno deve ser definida como zero. |
| As associações Corporativa e Individual possuem cobrança de taxa. | A taxa deve ser maior que zero para esses tipos de associação. |
| Alguns tipos de associação oferecem privilégios aos membros. | Os privilégios devem estar relacionados ao tipo de associação cadastrado. |
| O tipo de associação de um membro não pode ser alterado livremente. | A alteração do tipo de associação deve exigir uma justificativa válida. |
| Novos tipos de associação podem ser adicionados futuramente. | O modelo deve permitir o cadastro de novos tipos sem comprometer os registros existentes. |

### 2. Hospital Star Care

| Regra de negócio | Constraint associada |
|---|---|
| Todo médico registrado no hospital deve possuir um identificador exclusivo. | O ID do médico deve ser `UNIQUE`. |
| O identificador dos médicos deve começar com `DC`. | O ID deve seguir o padrão definido, iniciando com `DC`. |
| Os médicos devem possuir pelo menos sete anos de experiência profissional. | O tempo de experiência deve ser maior ou igual a 7 anos. |
| Todo paciente deve ser registrado no hospital antes ou durante sua primeira consulta. | O paciente deve possuir um cadastro antes de ser associado a uma consulta. |
| Cada paciente deve possuir um número de identificação exclusivo. | O número do paciente deve ser `UNIQUE`. |
| O número de identificação dos pacientes deve começar com `PT`. | O número do paciente deve seguir o padrão definido, iniciando com `PT`. |

### Conclusão

A análise dos cenários permite identificar as regras que determinam o funcionamento dos sistemas e as restrições necessárias para garantir a integridade dos dados. Essas regras podem posteriormente ser implementadas no banco de dados por meio de constraints, validações e relacionamentos entre as tabelas.
