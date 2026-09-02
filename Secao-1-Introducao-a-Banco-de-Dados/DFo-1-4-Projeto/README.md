# DFo 1-4: Projeto

## Descrição

Atividade de identificação dos requisitos de negócio da Oracle Baseball League (OBL), considerando suas regras de negócio, suposições, problemas e necessidades para auxiliar na criação do modelo de dados do sistema.

## Exercício — Requisitos do Negócio

### 1. Regras de Negócio

| Regra de negócio | Descrição |
|---|---|
| Tipos de clientes | A OBL possui clientes individuais e clientes que representam equipes. |
| Produtos | Os clientes podem comprar qualquer item disponível no estoque. |
| Compras de equipes | As equipes podem comprar uniformes e equipamentos para seus jogadores. |
| Desconto para equipes | As equipes recebem desconto sobre o preço de lista dos produtos, de acordo com o número de jogadores. |
| Pedidos | Cada pedido deve registrar os itens que foram adquiridos pelo cliente. |
| Representantes de vendas | A OBL possui três representantes de vendas responsáveis oficialmente pelo atendimento das equipes. |
| Atendimento a clientes individuais | Embora atendam oficialmente as equipes, os representantes também podem tratar reclamações de clientes individuais. |
| Estoque | Os produtos comercializados pela OBL devem ser mantidos em um cadastro de estoque. |
| Preço dos produtos | Cada item disponível para venda deve possuir um preço de lista. |

### 2. Suposições

| Suposição | Descrição |
|---|---|
| Cadastro de clientes | Cada cliente deve possuir um cadastro com informações que permitam sua identificação e contato. |
| Cadastro de equipes | As equipes devem possuir um cadastro próprio para que possam ser identificadas nos pedidos e relacionadas aos clientes que as representam. |
| Número de jogadores | O número de jogadores de uma equipe deve ser registrado para determinar o desconto aplicável. |
| Cadastro de produtos | Cada produto deve possuir informações como nome, descrição, preço e quantidade disponível em estoque. |
| Identificação dos pedidos | Cada pedido deve possuir um identificador único para facilitar seu controle. |
| Itens do pedido | Um pedido pode conter um ou mais produtos, sendo necessário registrar a quantidade de cada item adquirido. |
| Representante responsável | Um pedido ou atendimento de uma equipe pode ser associado ao representante de vendas responsável. |
| Controle de estoque | A quantidade disponível de cada produto deve ser atualizada conforme as vendas realizadas. |

### 3. Problemas e Necessidades

| Problema ou necessidade | Descrição |
|---|---|
| Controle de clientes | A OBL necessita controlar os dados dos clientes individuais e dos clientes que representam equipes. |
| Controle de equipes | É necessário armazenar informações das equipes e a quantidade de jogadores para calcular os descontos. |
| Controle de pedidos | A empresa precisa registrar os pedidos e os produtos presentes em cada pedido. |
| Controle de estoque | É necessário acompanhar a quantidade de produtos disponíveis para evitar problemas com vendas de itens sem estoque. |
| Cálculo de descontos | O sistema deve permitir determinar o desconto aplicado às equipes de acordo com o número de jogadores. |
| Controle dos representantes | A empresa precisa controlar os três representantes de vendas e os atendimentos realizados por eles. |
| Atendimento de reclamações | Como os representantes também atendem reclamações de clientes individuais, o sistema deve permitir registrar e acompanhar esses atendimentos. |

### Conclusão

A análise do cenário permite identificar os principais processos envolvidos na operação da OBL, como cadastro de clientes e equipes, controle de produtos e estoque, realização de pedidos, aplicação de descontos e atendimento pelos representantes de vendas. Esses requisitos servem como base para a criação do modelo de dados do sistema.
