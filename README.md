# Arte dos Dados - Projeto 3


## 📘 Projeto 3 — Car Insurance Claim Prediction

Este projeto tem como objetivo desenvolver um modelo de classificação capaz de prever a probabilidade de um segurado realizar um sinistro (claim). O dataset inclui múltiplas informações sobre os segurados e suas características, permitindo a construção de um pipeline completo de ciência de dados.

## 📂 Estrutura Geral do Projeto

O notebook contém todas as etapas essenciais de um fluxo de Machine Learning, incluindo preparação dos dados, análise exploratória, engenharia de atributos, treinamento de modelos e avaliação de desempenho.

Também está disponível em: <https://colab.research.google.com/drive/15DtNG9Qb-OSuNSm5nQzMiFCxNNmFJJlM?authuser=1#scrollTo=ttaQpNMa2jfr&uniqifier=1>.

## 🎯 Objetivos do Projeto

- Construir um modelo de classificação para prever sinistros.

- Preparar o dataset por meio de limpeza, tratamento de valores extremos e variáveis categóricas.

- Comparar algoritmos e selecionar o modelo com melhor desempenho.


## 📑 Etapas do Processo

1. Padronização dos nomes das colunas

a) Todas as colunas são convertidas para letras minúsculas para evitar inconsistências no tratamento e manipulação.

b) Remoção de caracteres especiais utilizando expressões regulares, garantindo compatibilidade e segurança no carregamento dos dados.

2. Tratamento dos Outliers

a) Identificação de valores extremos em variáveis contínuas.

b) Aplicação de técnicas estatísticas para identificar e corrigir outliers, com cálculo de limites e documentação dos ajustes efetuados.

3. Tratamento dos Missing Values

a) Mapeamento de colunas com dados ausentes.

b) Aplicação de estratégias de imputação conforme o tipo e impacto da variável.

4. Processamento de Dados Categóricos

a) Conversão de categorias para formatos numéricos apropriados.

b) Estratégias como one-hot encoding ou similares são aplicadas conforme necessidade do modelo.

5. Análise Exploratória de Dados (EDA)

a) Avaliação das distribuições das variáveis.

b) Identificação de relações entre features e a variável-alvo.

c) Verificação de correlações e padrões relevantes ao modelo.

6. Seleção de Features

a) Escolha das variáveis mais relevantes para o desempenho dos modelos.

b) Eliminação de redundâncias e variáveis pouco informativas.

7. Divisão dos Dados

a) Divisão entre treino (80%) e teste (20%), garantindo boa representatividade estatística.

8. Treinamento dos Modelos

a) Experimentação com algoritmos de Machine Learning para classificação.

b) Ajuste fino de parâmetros e comparação de performance.

9. Métricas de Avaliação

a) Avaliação dos modelos utilizando:

b) Acurácia

c) F1-score

d) Matriz de confusão

e) Outras métricas pertinentes à classificação

10. Seleção do Melhor Modelo

a) Análise comparativa entre todos os algoritmos testados.

b) Escolha do modelo final com melhor desempenho e interpretabilidade.

## 📦 Dados Utilizados

Os arquivos foram importados diretamente no notebook e possuem informações completas sobre sinistros e características dos segurados. A estrutura e origem do dataset devem estar descritas na documentação do trabalho fornecido pela instituição.

## ▶️ Como Executar o Projeto

1) Certifique-se de possuir Python 3.x e as bibliotecas usadas no notebook.

2) Abra o arquivo Projeto3.ipynb em Jupyter Notebook, Jupyter Lab ou VSCode.

3) Execute as células em ordem para reproduzir todo o pipeline analítico.

## 📝 Observações Finais

Este notebook apresenta um pipeline completo de preparação, análise e modelagem para predição de sinistros em seguros automotivos. Ele pode servir tanto como base para estudos quanto como parte de um sistema de predição mais robusto.



