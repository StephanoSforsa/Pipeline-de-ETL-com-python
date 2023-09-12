# Construção de um Pipeline de ETL com Python

Este projeto demonstra uma aplicação básica do processo de ETL, conforme abordado durante o Santander Bootcamp 2023 - Ciência de Dados com Python, através da plataforma da DIO.

## Extração de Dados

Para simular a extração de dados, inicialmente foram gerados dados fictícios de 10 clientes, incluindo seus nomes, números de identificação, altura (em centímetros) e peso (em quilogramas). Esses dados simulados foram armazenados no formato CSV e posteriormente foram importados e transformados em um DataFrame.

## Tratamento de Dados

No processo de tratamento de dados, foram realizadas as seguintes transformações:

1. Conversão da coluna de altura do formato em centímetros para metros.
2. Arredondamento dos valores das colunas peso e altura para duas casas decimais.
3. Cálculo do Índice de Massa Corporal (IMC) para cada cliente.
4. Classificação da faixa de IMC em que cada cliente se enquadra.

## Load

Em seguida, na etapa de load, os novos dados foram exportados para um arquivo no formato 'XLSX', em uma planilha do Excel.
