# ETL Pipeline for Personalized Instagram Profile Recommendations

## Descrição
Meu primeiro pipeline de ETL. Este pipeline de ETL extrai dados de um arquivo CSV contendo informações de usuários, transforma esses dados gerando recomendações personalizadas de perfis do Instagram com base nos interesses dos usuários utilizando a API do ChatGPT(foi usada uma função mock lugar da API, porém a função que usa a API está comentada logo acima), e carrega os dados transformados em um novo arquivo CSV com o perfis recomendados a cada usuário.

## Estrutura do Projeto

- `usuarios.csv`: Arquivo CSV de entrada com as informações dos usuários.
- `teste.ipynb`: Jupyter Notebook contendo o pipeline ETL.
- `usuarios_com_recomendacoes.csv`: Arquivo CSV de saída com as recomendações geradas.
