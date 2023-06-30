# IFood Dev Week 2023

Este projeto consistiu em uma imersão semanal em ciências de dados com Python, abrangendo conhecimentos desde lógica de programação até a aplicação de criar um analisador de feedbacks usando a API do Chat GPT, no estilo de calcular um Net Promoter Score (NPS).

## Objetivos do projeto

- Aprender os conceitos fundamentais de lógica de programação.
- Explorar o paradigma da orientação a objetos em Python.
- Utilizar a API do Chat GPT para análise de sentimentos em feedbacks.
- Aplicar conhecimentos de ETL (Extract, Transform and Load) em dados.
- Gerar gráficos do NPS a partir de um DataFrame do Pandas.

## Bibliotecas utilizadas

Foram utilizadas as seguintes bibliotecas:

- `gdown`: para realizar o download de arquivos necessários.
- `pandas`: para manipulação e análise de dados.
- `matplotlib`: para criação de gráficos.
- `matplotlib.patches`: para criação de patches personalizados.
- `openai`: para integração com a API do Chat GPT.

## Funcionalidades adicionais

Além das atividades propostas, foi abordado o conceito de ETL, em que os dados foram extraídos, transformados e carregados no formato adequado para análise. Também foi realizada uma modificação no código original da chamada da API do Chat GPT para que a IA retornasse um JSON no formato `{"nps": "valor"}`, que foi utilizado como entrada para uma função desenvolvida durante o evento, capaz de gerar o gráfico do NPS com base nos dados importados como um DataFrame do Pandas.

## Licença

Este projeto está disponível para copiar, estudar e alterar o código.

Sinta-se à vontade para explorar o projeto, aprender com ele e adaptá-lo de acordo com suas necessidades.
