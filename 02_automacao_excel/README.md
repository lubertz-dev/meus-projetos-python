# Automação de Relatórios com Pandas

Este projeto foi desenvolvido para automatizar a geração de relatórios individuais a partir de uma base de dados unificada.

## O que o script faz:
1. Lê uma base de dados geral de vendas em Excel utilizando a biblioteca Pandas.
2. Remove duplicatas para identificar a lista única de vendedores.
3. Percorre a lista de vendedores e filtra as vendas de cada um.
4. Cria um arquivo Excel individual (Relatório Vendas [Nome].xlsx) para cada vendedor, contendo apenas os seus respectivos dados.

## Tecnologias utilizadas:
- Python
- Pandas (Manipulação e análise de dados)
- Openpyxl / XlsxWriter (Exportação para Excel)

## Como rodar:
Certifique-se de ter as bibliotecas instaladas (pip install pandas openpyxl xlsxwriter), mantenha o arquivo Vendas_Jan.xlsx na mesma pasta e execute o arquivo .ipynb.
