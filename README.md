# 4-Power-BI-Analise-Pedidos

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

##  Medidas DAX

<br>

<div align="center">
<img src="https://github.com/user-attachments/assets/6d5ad201-c95f-4f4e-8800-afb72db8a535" />
</div>

## Respondendo a 1º solicitação do CEO:

<br>

<div align="center">
<img src="https://github.com/user-attachments/assets/316949f8-b640-4771-8811-a918a9469589" />
</div>

<br>
<br>

<div align="center">
<img src="https://github.com/user-attachments/assets/4e3a73b6-1906-4e37-ad38-906efca993a7" />
</div>

<br>

### Meta Variavel:
   *Permite que o CEO ajuste de acordo com a meta que ele queira ver, tornando uma visualização dinamica em tempo real.*
   *Atualizando o cartão "Vendedores que bateram a meta"*

## Respondendo a 3º solicitação do CEO:

<div align="center">
<img src="https://github.com/user-attachments/assets/05fd9b33-cc5c-4a46-828b-9e97b1d3b318" />
</div>

<br>

<div align="center">
<img src="https://github.com/user-attachments/assets/38144eb3-8906-4640-8c4b-008fa9786b1e" />
</div>

<br>

## Respondendo a 5º solicitação do CEO:

<br>

<div align="center">
<img src="https://github.com/user-attachments/assets/321f8896-569f-4ddd-9f75-83dbb0c5275a" />
</div>

<br>

### Função Filter:
   *Retorna uma tabela que representa um subconjunto de outra tabela ou expressão.*

### Função Values:
   *Quando o parâmetro de entrada é um nome de coluna, retorna uma tabela de uma coluna que contém os valores distintos da coluna especificada.*
   *Valores duplicados são removidos e apenas valores exclusivos são retornados.*

<br>

---

# Dashboard

<br>

<div align="center">
<img src="https://github.com/user-attachments/assets/e4b6c450-61f1-4a31-afaa-48747f83203e" />
</div>

<br>

### Cartões:
* Soma de Vendas
* Quantidade de Vendedores
* Valor médio por item vendido
* Vendedores que bateram a meta
* Ticket Médio de vendas por Vendedor

### Segmentações:
* Meta Variavel
* Sellers ID
* State do Vendedor
### Gráficos:

* Funil de Sellers X Maior Frete
* Mapa de Vendas X Localização (Granularidade de País, Estado e Cidade)
* Tabela de Sellers ID, Soma de Frete (Com formatação condicional), Média de Frete e Frete Acima de 25K (Com formatação condicional).

