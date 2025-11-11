# 4-Power-BI-Analise-Pedidos

Painel Interativo utilizando **Análise de Inteligência Temporal** com a criação de uma **tabela calendário**.

# O Problema de Negócio:

O CEO quer saber como a empresa está avançando em relação as metas estabelecidas para o ano atual e como a empresa está posicionada em relação aos dados de anos anteriores, ou seja, a partir desse ponto o CEO deseja explorar **análises de inteligência temporal**.

# Solicitações do CEO:

### Cartões:

* Quantidade de pedidos
* Quantidade de clientes
* Quantidade de pedidos do ano de 2017
* Quantidade de pedidos do ano de 2018
* Taxa de Crescimento (2017 - 2018)

### Gráficos:

* Quantidade de pedidos x Meta Anual
* Quantidade de pedidos x Meta Mensal de 2018
* Quantidade de Pedidos por Estado do Cliente

### Segmentações:

* Detalhes da quantidade de pedidos e meta de pedidos por Ano, Mês, estado do Cliente e Cidade do Cliente
* Data de Compra
* Ano / Mês (de compra)
* Estado do Cliente
* Cidade do Cliente
* Status do Pedido

##  Medidas DAX / Tabela Calendário

<br>

<div align="center">
<img src="https://github.com/user-attachments/assets/5fe7a3f3-82bc-436f-8747-24efa7f2254e" />
</div>

## DAX Ano Anterior:

<br>

<div align="center">
<img src="https://github.com/user-attachments/assets/7ce1dfe7-162b-4873-b52f-eeb416802d8a" />
</div>

<br>

* A função **SAMEPERIODLASTYEAR** é uma função de **inteligência de dados temporais** que retorna uma tabela que contém uma coluna de datas deslocadas para um ano antes das datas na coluna dates especificada, no
contexto atual.

* No exemplo, através da expressão **COUNTROWS** contamos a quantidade de linhas da tabela orders.
* Ao passar como argumento de filtro a função **SAMEPERIODLASTYEAR**, faremos a contagem de linhas de um ano antes relacionado ao contexto que estamos analisando.

  <br>

  ## Dax Pedidos 2017 / 2018:

<div align="center">
<img src="https://github.com/user-attachments/assets/d72f15cf-a228-4a8e-804b-fa7a43a1ff1f" />
</div>

<br>

<div align="center">
<img src="https://github.com/user-attachments/assets/96246fe9-47ca-4887-9c3d-2168341abebd" />
</div>

---

# Dashboard

<br>

<div align="center">
<img src="https://github.com/user-attachments/assets/cf8702f4-908f-4432-be81-8430a0f8d855" />
</div>

<br>



