# Projeto Final - Banco de Dados Avançado

**Curso:** Sistemas para Internet
**Disciplina:** Banco de Dados Avançado
**Professor:** Aramis
**Período:** P3



## Grupo CONDOMINIO

**Integrantes:**

* Francielly Ariel Brasil (Revisora e ajustes finais)
* Marinalva Dos Santos
* Eugenia Guedes
* Felipe Cartaxo
* Luana Jessica Ferreira da Silva



## Objetivo Geral

Um sistema de admnistração de condominio 



## Quem fez o quê

### 🔹 Eugenia Guedes – Procedures e Índices

**Função:** Organização o geral, validar se tudo tá integrado e funcionando.
**O que fez:**

* Criou 3 procedures, sendo:

  * Uma com cursor (que foi meio chatinha hehe).
  * Uma com vários parâmetros opcionais pra flexibilizar as consultas.
* Criou 3 índices, um deles composto (pra melhorar performance).
* Usou EXPLAIN e ANALYZE pra medir desempenho das queries.
* Escreveu a parte do desempenho no PDF (que ficou bem massa).


### 🔹 Marinalva Dos Santos – Modelagem e Subconsultas

**Função:** Montar o banco, criar a estrutura lógica e fazer subconsultas.
**O que fez:**

* Criou e ajustou as tabelas principais do banco.
* Fez 5 subconsultas, tipo:

  * No FROM, no SELECT, com EXISTS/NOT EXISTS, e duas com funções agregadas.
* Fez o diagrama relacional (usou dbdiagram.io).
* Escreveu tudo sobre modelagem no relatório (PDF).



### 🔹 Felipe Cartaxo – Functions

**Função:** Criar funções que automatizam o banco.
**O que fez:**

* Criou 3 funções, sendo:

  * Uma que retorna um tipo escalar (número, texto, etc).
  * Uma que retorna uma tabela temporária (tipo uma lista mesmo).
  * Uma que trata erro usando IF, CASE e SIGNAL (um pouco de gambiarra às vezes).
* Explicou a lógica dessas funções no PDF técnico.



### 🔹 Luana Jessica – Triggers

**Função:** Fazer o banco reagir automaticamente (gatilhos).
**O que fez:**

* Criou 3 triggers:

  * Uma pra auditoria (logando as mudanças).
  * Uma que mexe com mais de uma tabela (coisa de mestre rs).
  * Uma que muda comportamento padrão, tipo bloqueando update indevido.
* Escreveu explicações detalhadas sobre esses gatilhos no PDF.



### 🔹 Francielly Ariel Brasil – Revisora e Ajustes Finais

**Função:** Dar uma geral final, revisar, ajeitar detalhes e organizar tudo.
**O que fez:**

* Revisou os scripts e a documentação (tentou achar bugs de digitação).
* Ajustou e formatou o relatório final (PDF).
* Organizou o README.md.
* Organizou as pastas e arquivos sql e docs.


## Como usar esse projeto

1. Cria o banco de dados no PostgreSQL (pode ser local ou na nuvem).
2. Roda os scripts de criação das tabelas (atenção pra ordem, que tem dependência).
3. Roda os scripts das procedures, functions, triggers e índices.
4. Insere uns dados de teste pra poder experimentar.
5. testa com os codigos teste cases!


## Estrutura do projeto

* Tabelas(Tem)
* Procedures(Tem)
* Functions(Tem)
* Triggers(Tem)
* Índices(Tem)
* Consultas avançadas(Tem)

