# Descrição do projeto

Uma empresa de varejo fictícia, possui milhares de clientes. Com o objetivo de aumentar o faturamento e o lucro da empresa, a diretoria quer conseguir identificar quem é o cliente ideal para seus produtos, baseado no histórico de compras dos clientes. Para isso, ela fez o trabalho de classificar os clientes com uma nota de 1 a 100. A partir dessa classificação, o perfil do cliente ideal da empresa, deve ser determinado.


As características do cliente ideal, que devem ser definidas de acordo com a empresa, é:
* Idade;
* Profissão;
* Tempo de experiência e;
* Quantidade de pessoas, que compõe a família do cliente.

 ### Roteiro para análise


 ### Base de dados

 A base de dados foi fornecida durante um treinamento, pela empresa Hashtag Programação.
 Canal no Youtube: https://www.youtube.com/@HashtagProgramacao

 Essa base de dados, possui o cadastro de 1965 clientes com os atributos:

| **Atributos** | **Descrição** |
| ------------------- | ------------------- |
| ClienteId | Número de identificação do cliente |
| Origem | Origem da venda (Promoção/Normal) |
| Idade | Idade do cliente |
| Salário Anual (R$) | Salário de um período de um ano do cliente |
| Nota (1 - 100) | Nota atribuída ao cliente, levando em consideração o histórico de compras do cliente |
| Profissão | Profissão do cliente |
| Experiência Trabalho | Tempo de experiência na profissão |
| Tamanho família | Quantidade de pessoas que compõe a família do cliente |


### Tratamento dos dados

Inicialmente, a base de dados continha 2000 registros, porém, 35 delas possuiam dados nulos (NA) na coluna profissão. Como esse atributo é importante na definição do perfil ideal do cliente, optou-se por excluir o registro desses clientes, da base de dados.

### Análise dos dados

O gráfico abaixo apresenta a frequência de vendas n promoção, e vendas normais:

<div align="center">
<img src="img/origem.png" />
</div>

