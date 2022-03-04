# Desafio-Pandas

Analise de um conjunto de transações feitas por um investor de criptomoeda. Para quem não conhece do que se trata, considere basicamente você comprando algo por um valor e revendendo por um valor maior para lucrar a diferença (basicamente).

### Conjunto de Dados
O conjunto de dados representa um conjunto de transações que aconteceram em um determinado intervalo, de modo que várias compras podem acontecer, até que o investidor decide zerar sua posição (vendendo tudo que comprou até então). Estão disponíveis as seguintes informações:

* buy_timestamp: quando aconteceu a primeira compra do conjunto de transações
* buy_price: preço pago por uma unidade da criptomoeda na primeira compra (é possível comprar frações)
* batch_invested_amount: total investido em dólares em todas as compras realizadas
* asset_amount: fração da criptomoeda adquirido com a quantidade em dólares investida
* buyTimes: quantas vezes aconteceram compras antes de se realizar a venda
* sell_timestamp: quando aconteceu a venda (zerar posição)
* sell_price: preço pelo qual foi vendido
* minimal_roi: nome da estratégia utilizada para fazer a venda
* result: resultado após a venda (lucro ou prejuízo em dólares)
* total_wallet: total da carteira após o conjunto de transações ter sido efetivado

>Obs.: A carteira do investidor começou com 10 mil dólares.

O desafio consiste em desenvolver um estudo utilizando Pandas e gráficos para apresentar uma análise para esse investidor.
