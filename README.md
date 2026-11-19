# Análise de Dados: Pesquisa State of Data Brazil 2022 (Data Hackers)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Naty-29/analise-dados/blob/main/analise_dados.ipynb)

Projeto de análise exploratória dos dados da pesquisa anual da **Data Hackers de 2022**, uma das principais fontes de informação sobre o mercado de trabalho na área de Tecnologia da Informação (TI) no Brasil.

## Objetivos

1. **Aprender e praticar** técnicas de análise de dados com Python e as bibliotecas pandas, matplotlib e seaborn.
2. **Extrair insights** sobre o mercado de trabalho em TI, identificando padrões, tendências e correlações nos dados.

A análise olha para salários, níveis de escolaridade e tecnologias mais usadas, com um foco especial no **debate sobre diversidade**: representatividade de gênero e raça no campo da tecnologia.

## O que o notebook aborda

| Etapa | Conteúdo |
|---|---|
| Uso do pandas | Leitura da base (Excel) e primeiras explorações |
| Repetindo a análise do Excel | Reprodução em Python de análises feitas antes em planilha |
| Estatística básica | Medidas de tendência central e dispersão |
| Valores faltantes | Tratamento das colunas de gênero, idade e salário |
| Outliers | Identificação de valores discrepantes com boxplots |
| Distribuição amostral | Cálculo de intervalo de confiança com SciPy |
| Feature engineering | Criação de novas variáveis a partir da base |
| Correlação | Correlação entre idade e salário e teste qui-quadrado entre variáveis categóricas |
| SQL com pandas | Consulta a uma base SQLite com renda por município/estado e cruzamento com os salários |
| Visualização de dados | Gráficos com matplotlib, seaborn e Plotly (distribuição por gênero, salário médio por idade, dispersão salário × idade) |

## Tecnologias

- Python
- pandas e NumPy
- SciPy (estatística, intervalo de confiança, qui-quadrado)
- SQLite (`sqlite3`)
- matplotlib, seaborn e Plotly
- Google Colab

## Como executar

1. Clique no botão **Open in Colab** acima.
2. O notebook lê os arquivos de dados a partir do Google Drive (pasta `Análise de dados: Programaria`). Para rodar, coloque as bases (`planilha_modulo3.xlsx`, `Planilha_Aula_parte2.xlsx`, `analise_dados.csv` e o banco `status_brasil`) no seu Drive e ajuste os caminhos nas células de leitura.
3. Execute as células em ordem.

## Contexto

Projeto desenvolvido durante o curso de Análise de Dados da **PrograMaria**.
