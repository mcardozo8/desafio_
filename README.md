# Desafio de Previsão de Demanda de Combustíveis

Este repositório contém o projeto realizado para previsão da demanda de gasolina e middle distillates, com base em dados públicos (JODI, EIA, entre outros). Todo o processo foi feito em Python, incluindo análise exploratória, modelagem estatística e exportação dos resultados finais para análise em dashboards.

## Estrutura do Projeto

- **Desafio_Marcos_Ream.ipynb**  
  Notebook Jupyter com todo o passo a passo: tratamento dos dados, criação de variáveis, modelagens (OLS, SARIMAX, etc), gráficos e exportação dos resultados.

- **gasolina_hist_prev.csv / middle_hist_prev.csv**  
  Bases contendo a série histórica e as previsões futuras (forecast) para demanda de gasolina e middle distillates.  
  Permitem comparar valores reais e previstos nos dashboards.

- **gasolina_exogenas_historico.csv / middle_exogenas_historico.csv**  
  Bases com as variáveis exógenas e covariáveis históricas usadas nos modelos de previsão, úteis para análises adicionais e construção de dashboards mais ricos.

## Abordagem do Projeto

1. **Coleta e tratamento dos dados:**  
   Dados públicos de demanda, preços, produção industrial, transporte, desemprego, inflação, entre outros, foram integrados e tratados.

2. **Modelagem Preditiva:**  
   Foram testados modelos estatísticos (OLS, SARIMAX) para previsão de demanda, tanto com quanto sem variáveis exógenas.  
   Foram incluídas dummies para eventos excepcionais (pandemia e crise de 2008).

3. **Exportação dos resultados:**  
   Os resultados das previsões e dados históricos foram organizados em arquivos `.csv` prontos para integração com dashboards (ex: Power BI).

## Como usar

1. Clone este repositório ou faça o download dos arquivos.
2. Abra o notebook `Desafio_Marcos_Ream.ipynb` para ver todo o passo a passo do projeto.
3. Utilize os arquivos `.csv` para criar dashboards, análises ou relatórios.

## Observações

- Os dados brutos utilizados podem ser encontrados nos sites da [JODI](https://www.jodidata.org/), [EIA](https://www.eia.gov/) e [OPEC](https://www.opec.org).
- Os arquivos `.csv` finais já estão prontos para serem usados em ferramentas como Power BI ou Excel.

## Marcos Marçal
mcardozo8
