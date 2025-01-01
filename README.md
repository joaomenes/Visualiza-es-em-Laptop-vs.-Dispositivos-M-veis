Um desafio no qual me foi fornecida uma tabela com informações sobre visualizações de usuários, categorizadas por tipo de dispositivo: laptop, tablet e telefone. O objetivo era calcular o total de visualizações para laptops e dispositivos móveis, sendo que dispositivos móveis são definidos como a soma das visualizações de tablets e telefones.

Minha solução foi construir uma consulta SQL utilizando o comando CASE dentro de uma função SUM para contar as visualizações conforme as condições específicas.
Na minha consulta, utilizei o CASE para verificar o tipo de dispositivo. Se fosse um laptop, somava 1 à coluna laptop_views, e se fosse phone ou tablet, somava 1 à coluna mobile_views. O SUM foi responsável por calcular o total de visualizações para cada categoria.

A saída esperada era o total de visualizações para laptops e para dispositivos móveis (soma de tablet e telefone). No exemplo dado, obtive 2 visualizações para laptops e 3 para dispositivos móveis, validando o raciocínio por trás da consulta.

<h1>Exemplos de saída e as tabelas</h1>

![image](https://github.com/user-attachments/assets/36126ef1-a5ec-4942-bae0-3b277554e20e)
