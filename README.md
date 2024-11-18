# Análise de Dados de Lançamentos Espaciais

Este projeto utiliza Python e Pandas para realizar a análise de um conjunto de dados contendo informações sobre lançamentos espaciais realizados por diversas empresas ao redor do mundo.

## Descrição do Projeto

O objetivo deste projeto é explorar e responder a perguntas sobre os dados de missões espaciais, como:
- Qual é o país mais ativo em lançamentos espaciais?
- Quais são as missões mais caras realizadas?
- Como os lançamentos se distribuem ao longo do tempo?
- Qual é a taxa de sucesso das missões?

## Dados Utilizados

O arquivo `Space_Corrected.csv` contém as seguintes colunas principais:
- `Company Name`: Nome da empresa responsável pelo lançamento.
- `Location`: Localização do lançamento.
- `Datum`: Data do lançamento.
- `Detail`: Detalhes sobre a missão.
- `Status Rocket`: Status do foguete utilizado.
- `Rocket`: Custo estimado do foguete em milhões de dólares.
- `Status Mission`: Status da missão (e.g., Sucesso, Falha).

## Tecnologias Utilizadas

- Python
- Pandas

## Como Utilizar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   
2. Instale as dependências necessárias
   ```bash
   pip install pandas

3. Execute o script de análise:
    ```bash
    python scripts/analysis.py

## Exemplos de Saída
- A missão mais cara realizada foi de 145 milhões de dólares, com status de sucesso.
- O país mais ativo em lançamentos é EUA.
- A maioria dos lançamentos ocorre no verão.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou um pull request.
