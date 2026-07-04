# Projeto RH - SQL Server

Projeto desenvolvido para praticar conceitos de Banco de Dados utilizando SQL Server.

## Objetivo

Criar um banco de dados de Recursos Humanos contendo informações sobre:

- Funcionários
- Departamentos
- Cargos
- Histórico de Promoções

Além da modelagem do banco, o projeto contempla consultas SQL de diferentes níveis de complexidade.

## Estrutura do Banco

### Tabelas

- `departamentos`
- `cargos`
- `funcionarios`
- `historico_promocoes`

## Conteúdo Desenvolvido

### Nível Básico

- Criação do banco de dados
- Criação das tabelas
- Inserção de dados
- Total de funcionários por departamento
- Média salarial geral
- Top 10 maiores salários

### Nível Intermediário

- JOIN entre tabelas
- Subconsultas
- Percentual de distribuição de funcionários
- Comparação salarial entre departamentos
- Funcionários com maior tempo de empresa

### Nível Avançado

- Common Table Expressions (CTEs)
- Window Functions
- LAG() e LEAD()
- Ranking com RANK()
- Cálculo de turnover por departamento
- Views reutilizáveis
- Análises gerenciais

## Tecnologias

- SQL Server 2022
- SQL Server Management Studio (SSMS)
- T-SQL

## Estrutura do Projeto

```
ProjetoRH/
│
├── scripts/
│   ├── 01-criacao-banco.sql
│   ├── 02-criacao-tabelas.sql
│   ├── 03-inserts.sql
│   ├── 04-consultas-basicas.sql
│   ├── 05-consultas-intermediarias.sql
│   └── 06-consultas-avancadas.sql
│
└── README.md
```

## Aprendizados

Durante o desenvolvimento deste projeto foram praticados conceitos como:

- Modelagem Relacional
- Chaves Primárias e Estrangeiras
- Normalização
- JOINs
- Subconsultas
- CTEs
- Window Functions
- Views
- Agregações
- Funções Analíticas
- Boas práticas em SQL Server

## Autor

Daniel Augusto Gomes

LinkedIn:
https://www.linkedin.com/in/danielaugustogomes/

---
Projeto desenvolvido para estudos de SQL Server e Banco de Dados.