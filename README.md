# Projeto de Análise Exploratória e Pré-processamento de Dados

Este repositório contém um projeto focado na **análise exploratória** e **pré-processamento** de um conjunto de dados, com o objetivo de preparar os dados para modelagem preditiva e responder a questões de negócio. O projeto foi desenvolvido utilizando **Python** e bibliotecas como **Pandas**, **Matplotlib**, **Seaborn** e **Scikit-learn**.

## Objetivo do Projeto

O objetivo principal deste projeto é realizar uma análise exploratória detalhada dos dados, identificar padrões e realizar o pré-processamento necessário para aplicar técnicas de Machine Learning em modelos preditivos. Em particular, estamos interessados em:

1. Analisar a relação entre variáveis como idade, salário, frequência de compras e valor de compras.
2. Explorar a relação entre diferentes regiões e as compras realizadas.
3. Criar categorias para valores de compra e utilizar algoritmos de classificação, como Árvores de Decisão.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- **`Projeto-Analise-Exploratoria-e-Pre-processamento.ipynb`**: Jupyter notebook contendo todo o processo de análise exploratória e pré-processamento dos dados, com gráficos, insights e limpeza de dados.
  
- **Dataset**: O conjunto de dados foi pré-processado para incluir variáveis como idade, salário anual, frequência de compra e valor de compra. Variáveis categóricas foram codificadas para facilitar o uso em algoritmos de Machine Learning.

## Principais Etapas do Projeto

1. **Carregamento dos Dados**: Utilização do Pandas para carregar e entender o formato inicial dos dados.
  
2. **Análise Exploratória (EDA)**:
   - Visualização de dados utilizando **gráficos de barras**, **boxplots** e **histogramas**.
   - Identificação de outliers, valores ausentes e padrões nos dados.
  
3. **Pré-processamento**:
   - Normalização de variáveis numéricas, como idade, pressão arterial e colesterol.
   - Codificação de variáveis categóricas utilizando técnicas de One-Hot Encoding.
   - Criação de uma nova coluna para classificar o valor de compra em três categorias: Baixo, Médio e Alto.
   
4. **Modelagem Preditiva**:
   - Construção de um modelo de **Árvore de Decisão** para classificar as categorias de valor de compra.
   
## Ferramentas Utilizadas

- **Python**: Linguagem principal utilizada no projeto.
- **Pandas**: Para manipulação e limpeza dos dados.
- **Matplotlib/Seaborn**: Para visualização dos dados.
- **Scikit-learn**: Para pré-processamento e construção do modelo preditivo.
- **Jupyter Notebook**: Ambiente de desenvolvimento.

## Como Utilizar este Repositório

1. Clone este repositório para sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
