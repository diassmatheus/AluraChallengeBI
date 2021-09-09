 
# <p align="center"> <b> Dashboard de Logística </b> 

##  Motivação</br> </br> 

A pessoa que gerencia a área de logística da AluraShop está enfrentando algumas mudanças em sua área por conta do aumento da demanda dos serviços de logística no período da pandemia. Ela quer manter a qualidade de seu serviço, mas para isso precisa acompanhar constantemente as métricas do seu departamento para tomar as melhores decisões.

##  Base de Dados</br> </br> 

A base de dados consiste em quatro arquivos csv com a seguinte estrutura:

Tabela Pedidos

- Data do pedido
- Data de entrega
- Data previsão entrega
- ID pedido
- Latitude
- Longitude
- UF da entrega
- ID Produto
- Quantidade
- ID veículo
- Tabela Produtos

ID Produto

- Categoria Produto
- Valor

Tabela Estoque

- ID produto
- Data atualização
- Quantidade

Tabela Veículos

- ID veículo
- Tipo
- Status

A tabela de pedidos e estoque são tabelas de fatos e as restantes são dimensões.
