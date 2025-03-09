# Gerador de Menu da Semana

Este projeto é um gerador de menu semanal que permite criar um cardápio para a semana, 
gerar uma lista de compras com base no menu e salvar o resultado em um arquivo PDF. 
Além disso, ele permite adicionar novos itens ao menu (saladas, vegetais cozidos, carnes e pratos de jantar) e armazená-los em um banco de dados local.

## Funcionalidades

- **Gerar Menu da Semana**: Cria um menu aleatório para a semana, com almoço e jantar para cada dia.
- **Gerar Lista de Compras**: Gera uma lista de compras com base no menu criado.
- **Salvar PDF**: Salva o menu e a lista de compras em um arquivo PDF.
- **Adicionar Itens ao Menu**: Permite adicionar novos itens (saladas, vegetais cozidos, carnes e pratos de jantar) ao banco de dados.
- **Banco de Dados Local**: Armazena os itens do menu em um banco de dados SQLite.

## Pré-requisitos

Antes de executar o projeto, certifique-se de ter os seguintes requisitos instalados:

- **Python 3.8 ou superior**
- **Bibliotecas Python**:
  - `reportlab` (para gerar PDFs)
  - `sqlite3` (já vem com o Python)
  - `tkinter` (já vem com o Python)

Para instalar as bibliotecas necessárias, execute o seguinte comando:

```bash
pip install reportlab
