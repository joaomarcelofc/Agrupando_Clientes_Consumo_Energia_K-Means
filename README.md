# Agrupando clientes por Consumo de Energia com Algoritmo K-Means


A partir de dados de consumo de energia de clientes, nosso trabalho é agrupar os consumidores por similaridade a afim de compreender o comportamento dos clientes e sua relação com o consumo de energia.

<p align="center">
  <img src= "k-means.png"width=80% >
</p>

A base de dados utilizada em nosso projeto pode ser acessada pelo link abaixo:

https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption

Vamos executar as seguintes tarefas:

1- Tratar os valores ausentes nos dados.

2- Coletar uma amostra de 1% dos dados para criar o modelo de clusterização com o K-Means.

3- Encontrar o melhor valor de K para esse conjunto de dados.

4- Criar o modelo K-Means usando o valor de K encontrado no item 3.

5- Criar um Meshgrid para visualização de todos os clusters.

6- Visualizar os centróides.

7- Calcular o Silhoutte Score.

8 - Calcular a média de consumo de energia por cluster (usar a coluna Global_active_power para o cálculo da média).
