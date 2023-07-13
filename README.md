# Previsibilidade do Padrão Inflacionário

Este projeto tem como objetivo desenvolver um modelo de previsão do padrão inflacionário com base em dados históricos do IPCA e IPCA-15. O modelo utiliza técnicas de aprendizado de máquina para realizar a previsão da variação do IPCA com base nos dados do IPCA-15.

## Descrição do Projeto

O objetivo deste projeto é explorar a relação entre o IPCA e o IPCA-15 e desenvolver um modelo capaz de prever a variação do IPCA com base nos dados do IPCA-15. O IPCA-15 é uma prévia do IPCA, divulgado mensalmente pelo IBGE. Utilizaremos dados históricos desses índices para treinar o modelo e avaliar sua capacidade de previsão.

## Dados

Os dados utilizados neste projeto são provenientes do IBGE e estão disponíveis no arquivo `inflacao.csv`. O arquivo contém as seguintes colunas:

- `referencia`: Período de referência no formato YYYY-MM.
- `ipca_variacao`: Variação do IPCA no período de referência.
- `ipca15_variacao`: Variação do IPCA-15 no período de referência.

## Instalação

1. Clone este repositório para o seu ambiente local.
2. Certifique-se de ter as dependências necessárias instaladas. Você pode usar o arquivo `requirements.txt` para instalar as dependências com o seguinte comando:
   ```
   pip install -r requirements.txt
   ```
3. Execute o Jupyter Notebook `previsao_inflacionaria.ipynb` para explorar o código e executar as análises e previsões.

## Resultados

Os principais resultados deste projeto incluem:

- Análise exploratória dos dados históricos do IPCA e IPCA-15.
- Desenvolvimento de um modelo de previsão da variação do IPCA com base nos dados do IPCA-15.
- Avaliação do desempenho do modelo por meio de métricas de avaliação, como MAE e MSE.

## Contribuição

Contribuições são bem-vindas! Se você tiver sugestões de melhorias, correções de bugs ou novas funcionalidades, fique à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto é licenciado sob a [MIT License](LICENSE).
```
