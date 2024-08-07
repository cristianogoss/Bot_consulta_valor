# Automação de Consulta de Preços

Este projeto é um script em Python que automatiza a consulta de preços do Cimento no site da Tumelero Materiais para Construção, e atualiza uma planilha Excel com os preços coletados a cada 30 minutos.

## Funcionalidades

1. **Consulta Automatizada**:
   - Acessa o site da Tumelero.
   - Verifica o preço atual do Cimento.
   - Guarda o valor do preço (somente o valor numérico).

2. **Manipulação de Planilhas**:
   - Cria uma planilha com as seguintes colunas:
     - Produto (nome do produto)
     - Data atual (data da consulta)
     - Valor (preço do produto)
     - Link (link direto para o produto)

3. **Automatização Recorrente**:
   - Cria um agendamento para que o script rode a cada 30 minutos.

## Requisitos

- Python 3.x
- Bibliotecas:
  - `selenium`
  - `datetime`
  - `openpyxl`
  - `schedule`

##Instale as dependências
pip install -r requirements.txt

##Execute o script
python app.py

