**<h1> Desafio 1: Dashboard de Logística</h1>**
# 🚛 [Acessar o Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOTIwMDQzMGQtNDUwMC00Njc0LWI5M2MtZjU4YTU4MjEzYjA4IiwidCI6ImQ0NDEzYjc1LWUxZWYtNGViYi1hZGIzLWFlZThmZTBlZDJlNSJ9&pageName=ReportSectionefcfe0e64d15920c0688)

<br>

### Situação problema

A pessoa que gerencia a área de logística da Alura Log, está enfrentando algumas mudanças em sua área por conta do aumento da demanda dos serviços de logística no período da pandemia. Ela quer manter a qualidade de seu serviço, mas para isso precisa acompanhar constantemente as métricas do seu departamento para tomar as melhores decisões. 

<br>

### Ferramentas Utilizadas no Projeto

A extração, transformação e carga dos dados, bem como os painéis de visualização foram realizados com o Power BI Desktop e Power Query. 

<br>

### Requisitos

<ul>
  <li>Visualizar quantas entregas foram feitas no prazo;</li>
  <li>Visualizar quantas entregas foram feitas com atraso;</li>
  <li>Visualizar o número de veículos disponíveis;</li>
  <li>Exibir o índice de ocorrências por estado;</li>
  <li>Exibir o nível de estoque por ano;</li>
  <li>Calcular o Ship to Door (S2D) - tempo da ordem até a entrega em dias;</li>
  <li>Extra: Incluir outros insights relevantes.</li>
</ul>


<br>

### Base de Dados

Foram disponibilizadas 4 bases de dados para esse desafio, sendo elas:

  


<b>Tabela de Estoque</b>

<ul>
    <li>ID Produto</li>
    <li>Data atualização</li>
    <li>Quantidade</li>
</ul>




<b>Tabela de Pedidos</b>

<ul>
    <li>ID Pedido</li>
    <li>ID Produto</li>
    <li>Quantidade</li>
    <li>ID Veículo</li>
    <li>Status do pedido</li>
    <li>Data da compra</li>
    <li>Data da entrega</li>
    <li>Data previsão</li>
    <li>Latitude</li>
    <li>Longitude</li>
    <li>UF da entrega</li>
</ul>





<b>Tabela de Produtos</b>

<ul>
    <li>categoria_produto</li>
    <li>preço</li>
</ul>




<b>Tabela de Veículos</b>

<ul>
    <li>ID Veículos</li>
    <li>Tipo</li>
    <li>Status</li>
</ul>

### 
