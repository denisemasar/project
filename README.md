Análise de Dados – Partidas da Copa do Mundo

Autores - Grupo: 
Denise Maria de Assis Araújo  - git: denisea7@gmail.com
Itamar Vieira Maciel - git: itamarvmblack@gmail.com
Sérgio Pereira Domingos - git: domin.sergio@gmail.com

Curso: CAIXAVERSO - FC | Analista Dados - I | #1629

Módulo: Técnicas de Programação (PY) Professor: Rogério Mainardes

Projeto: Análise de Dados – Partidas da Copa do Mundo

Este projeto tem como objetivo analisar um conjunto de dados de partidas da Copa do Mundo utilizando Python e a biblioteca Pandas.

A proposta é aplicar técnicas básicas de tratamento, organização e análise de dados, respondendo perguntas a partir das informações presentes no dataset.

Objetivo

Explorar o dataset e extrair informações relevantes através de:

- Análise inicial dos dados
- Identificação de valores nulos
- Limpeza e organização das informações
- Criação de perguntas sobre o dataset
- Respostas utilizando operações do Pandas

Dataset

O dataset utilizado contém informações sobre partidas da Copa do Mundo, incluindo:

- Seleções participantes
- Placar da partida (Número de gols de cada Seleção)
- Posse de bola em percentual
- Número de assistências
- Número de gols de dentro da área e de gols de fora da área
- Número de chutes em direção ao gol e de chutes para fora
- Número de chutes de dentro da área e de chutes de fora da área
- Número de faltas cometidas
- Número de cartões amarelos e de cartões vermelhos
- Número de impedimentos
- Número total de passes e a quantidade de passes certos
- Número total de cruzamentos e a quantidade de cruzamentos certos
- Número de escanteios
- Número de cobranças de faltas
- Número de cobranças de pênaltis
- Número de defesas (gols salvos)
- Número de gols contra

Base de dados utilizada no projeto:

fifa_world_cup.csv

Biblioteca utilizada:

import pandas as pd

Etapas da análise
1. Importação dos dados

O dataset foi carregado utilizando a função:

pd.read_csv()

2. Exploração inicial

Primeiro foi feita uma análise da estrutura dos dados, observando:

- Tamanho da base de dados
- Tipos das  colunas
- Valores nulos
- Valores distintos


3. Tratamento de dados

Para melhorar a qualidade do dataset foram realizadas algumas etapas de limpeza:

- Remoção de valores nulos
- Remoção de registros duplicados
- Conversão de tipos de dados quando necessário

Funções utilizadas:

dropna()
drop_duplicates()
astype()
Perguntas analisadas

Durante o projeto foram levantadas 10 perguntas sobre o dataset:

Quais times fizeram mais gols?
Quais jogos tiveram mais gols?
Quais times tiveram maior posse de bola média?
Quais times deram mais chutes ao gol?
Quais times fizeram mais passes?
Quais jogos tiveram mais cartões amarelos?
Quais times sofreram mais faltas?
Quais times tiveram mais escanteios?
Quais times tiveram mais impedimentos?
Quais times apresebtaram maior pressão defensiva?

Técnicas utilizadas no Pandas

Durante a análise foram utilizadas operações como:

filtragem de dados
agrupamento de informações
ordenação de resultados
criação de novas colunas

Principais funções utilizadas:

groupby()
sort_values()
value_counts()
head()
Estrutura do repositório
project
│
├── fifa_world_cup.csv
├── projeto.ipynb
└── README.md

