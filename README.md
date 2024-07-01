# Databricks-Healthcare-Análise

## Objetivo
O objetivo deste trabalho é analisar a qualidade dos hospitais nos EUA usando o conjunto de dados "Informações Gerais do Hospital" disponível no Kaggle. Com base nesta análise, pretendo identificar os principais fatores que influenciam a qualidade dos hospitais e responder a perguntas específicas sobre o desempenho e a infraestrutura hospitalar.

## As perguntas que desejamos responder são:
1. Qual é a distribuição da classificação geral dos hospitais?
2. Existe uma correlação entre o número de leitos e a classificação do hospital?
3. Qual estado possui os hospitais com as melhores classificações gerais?

## Dados
Utilizaremos o conjunto de dados "Informações Gerais do Hospital" disponível no Kaggle.


## Etapas

### 1. Busca pelos Dados
Para alcançar os objetivos definidos, escolhi o conjunto de dados "Informações Gerais do Hospital" disponível no Kaggle. Esse conjunto de dados contém informações abrangentes sobre diversos hospitais nos EUA, incluindo classificações, estados, e outras métricas relevantes.

### 2. Coleta
Os dados foram coletados do Kaggle e armazenados no repositório do GitHub. O arquivo CSV foi carregado diretamente no Databricks a partir do link do GitHub, facilitando a integração e análise subsequente.

### 3. Modelagem
Os dados foram modelados usando um esquema flat, onde cada hospital possui atributos como ID, Nome, Estado, Classificação Geral e Número de Leitos. Essa modelagem simples permite uma análise direta e eficaz dos dados, facilitando a visualização e interpretação dos resultados.

### 4. Carga
Os dados transformados foram carregados no formato Parquet no armazenamento da nuvem, utilizando o Databricks. Esse formato otimizado permite uma manipulação eficiente dos dados durante a análise.

### 5. Análise
Nesta etapa, realizei uma análise detalhada da qualidade dos dados e da solução do problema. A análise de qualidade dos dados incluiu a verificação de valores ausentes, inconsistências e outras anomalias. A análise da solução do problema focou em responder às perguntas definidas inicialmente, utilizando ferramentas e técnicas apropriadas para extrair insights valiosos dos dados.

#### Qualidade dos Dados
A análise descritiva dos dados mostrou que...

#### Solução do Problema
1. **Distribuição da classificação geral dos hospitais:**
   - A maioria dos hospitais possui uma classificação de 3 estrelas.
2. **Correlação entre o número de leitos e a classificação do hospital:**
   - Não foi encontrada uma correlação significativa entre o número de leitos e a classificação do hospital.
3. **Estado com os hospitais de melhores classificações:**
   - O estado de Utah possui a maior média de classificação dos hospitais.

## Autoavaliação
O objetivo inicial foi atingido parcialmente. As principais dificuldades encontradas foram... 
Para trabalhos futuros, é possível explorar...







