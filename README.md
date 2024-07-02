###Descrição
Neste trabalho, construí um pipeline de dados utilizando tecnologias na nuvem, especificamente na plataforma Databricks Community Edition. O pipeline envolve a busca, coleta, modelagem, carga e análise dos dados.

###Objetivo
O objetivo deste trabalho é analisar a qualidade dos hospitais nos EUA utilizando um conjunto de dados do Kaggle. Desejo responder às seguintes perguntas:

###Qual é a distribuição da classificação geral dos hospitais?
###Existe uma correlação entre a experiência do paciente e a classificação geral do hospital?
###Qual estado possui os hospitais com as melhores classificações gerais?

###Plataforma
Utilizei a plataforma Databricks Community Edition para construir o pipeline de dados. Essa plataforma oferece ferramentas poderosas para processamento de dados em larga escala e análise de dados.

###Detalhamento

###1. Busca pelos dados
Escolhi o conjunto de dados "Hospital General Information" disponível no Kaggle. Esse conjunto de dados contém informações abrangentes sobre hospitais nos EUA, incluindo classificações e outras métricas relevantes.

###2. Coleta
Os dados foram coletados do Kaggle e armazenados no Databricks. O arquivo CSV foi carregado diretamente na plataforma.

###3. Modelagem
Construí um modelo de dados em Esquema Estrela para facilitar a análise dos dados. O modelo consiste nas seguintes tabelas:

###Tabela de Fatos:

HospitalRatings: Contém as avaliações agregadas dos hospitais.

###Tabelas de Dimensões:

Hospitals: Detalhes dos hospitais.
Locations: Informações sobre o estado e cidade dos hospitais.
Time: Datas relacionadas às avaliações e registros.

4. Carga
Carreguei os dados no Data Warehouse do Databricks utilizando um pipeline de ETL (Extração, Transformação e Carga). Documentei os processos de transformação e carga.

5. Análise
Dividi a análise em duas partes: qualidade de dados e solução do problema.

a. Qualidade de Dados
Realizei uma análise da qualidade dos dados para cada atributo do conjunto de dados. Verifiquei a existência de valores ausentes, duplicados ou inconsistentes e apliquei técnicas de limpeza de dados conforme necessário.

b. Solução do Problema
Respondi às perguntas elencadas nos objetivos, conectando os números obtidos às respostas ao problema a ser solucionado.

Implementação no Databricks







