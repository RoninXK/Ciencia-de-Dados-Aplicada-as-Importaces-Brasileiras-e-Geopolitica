# Ciência de Dados Aplicada às Importações Brasileiras e Geopolítica

## Sobre o Projeto

Este projeto foi desenvolvido como atividade prática de Ciência de Dados e Inteligência Artificial, utilizando dados reais das importações brasileiras para analisar padrões de comércio exterior e possíveis impactos de eventos geopolíticos internacionais.

O trabalho aplica etapas fundamentais de Ciência de Dados:

* Coleta de dados
* Limpeza e preparação
* Análise exploratória (EDA)
* Visualização gráfica
* Modelagem com Inteligência Artificial
* Interpretação dos resultados

## Objetivo

Investigar a evolução das importações brasileiras, identificar os principais países e produtos envolvidos no comércio internacional e demonstrar como técnicas de Ciência de Dados podem auxiliar na análise de cenários econômicos e geopolíticos.

## Tecnologias Utilizadas

* Python
* Pandas
* Matplotlib
* Scikit-Learn
* SQLite
* Jupyter Notebook

## Variáveis Utilizadas

As análises foram realizadas utilizando as seguintes variáveis da base de dados:

* CO_ANO
* CO_PAIS
* CO_NCM
* VL_FOB
* KG_LIQUIDO

## Base de Dados

A base utilizada neste projeto possui aproximadamente 3 GB e, por esse motivo, não foi incluída neste repositório.

Download da base:

https://www.kaggle.com/datasets/juniorfazzio/data-of-brazilian-import-and-export-data

Após realizar o download, coloque os arquivos na pasta:

dados/

## Principais Etapas Desenvolvidas

1. Carregamento da base de dados.
2. Seleção das variáveis relevantes.
3. Limpeza e tratamento dos dados.
4. Análise exploratória.
5. Construção de gráficos.
6. Treinamento de um modelo de Árvore de Decisão.
7. Geração de previsões e interpretação dos resultados.

## Como Executar

Instale as dependências:

```bash
pip install pandas matplotlib scikit-learn jupyter
```

Execute o Jupyter Notebook:

```bash
jupyter notebook
```

Abra o arquivo:

```text
tema2_importacoes.ipynb
```
