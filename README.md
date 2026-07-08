# Product Sales Analysis

Projeto desenvolvido em Python utilizando Google Colab para realizar o tratamento, limpeza e análise exploratória de dados de vendas de uma empresa de e-commerce.

---

# Sobre o Projeto

O objetivo deste projeto é explorar uma base de dados de vendas, aplicando técnicas de limpeza, transformação e análise de dados para identificar padrões de comportamento, inconsistências e indicadores relevantes para o negócio.

Todo o desenvolvimento foi realizado em Python, utilizando bibliotecas voltadas para manipulação de dados e visualização gráfica, seguindo um fluxo típico de um projeto de Análise Exploratória de Dados (Exploratory Data Analysis - EDA).

---

# Objetivos

1. Realizar o tratamento e limpeza da base de dados.

2. Padronizar informações textuais e corrigir inconsistências.

3. Explorar os principais indicadores de vendas.

4. Identificar padrões através de estatísticas e visualizações gráficas.

5. Demonstrar a utilização das principais bibliotecas de análise de dados em Python.

---

# Base de Dados

**Fonte:**

E-commerce Sales Dataset

**Descrição:**

A base de dados contém informações referentes às vendas de uma empresa de e-commerce, incluindo dados sobre produtos, clientes, pedidos e demais atributos necessários para análise.

---

# Ferramentas Utilizadas

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn *(caso tenha utilizado)*
- Git
- GitHub

---

# Etapas da Análise

## Importação dos Dados

Carregamento da base de dados e das bibliotecas necessárias para o desenvolvimento do projeto.

---

## Limpeza dos Dados

Durante esta etapa foram realizados procedimentos como:

- Tratamento de valores ausentes;
- Padronização de textos;
- Correção de inconsistências;
- Conversão de tipos de dados.

---

## Análise Exploratória

Após o tratamento dos dados foram realizadas análises estatísticas e gráficas para compreender o comportamento das variáveis presentes na base de dados.

---

## Visualizações

O projeto utiliza gráficos para facilitar a interpretação dos resultados obtidos durante a análise exploratória.


### Gráficos para análise da receita
<img width="691" height="539" alt="01_receita_por_categoria" src="https://github.com/user-attachments/assets/cc378e1c-b29f-470b-96f2-50fca40a2ec3" />
<img width="678" height="856" alt="02_receita_por_país" src="https://github.com/user-attachments/assets/bcb6a7d3-0ee5-430a-a5f6-e3c95ac27d08" />
<img width="700" height="736" alt="03_receita_por_região" src="https://github.com/user-attachments/assets/92e41b33-d323-45de-9e4e-9f931ad52220" />
<img width="647" height="581" alt="04_receita_por_canal_de_vendas" src="https://github.com/user-attachments/assets/d30e04a2-1f87-4fbb-9bc9-64c2ac9f8d26" />


### Gráficos relacionados à média de dias necesários para concluir a entrega dos produtos
<img width="848" height="540" alt="05_média_de_dias_por_categoria" src="https://github.com/user-attachments/assets/d1b67f26-4fdd-416d-a759-cf394700bee4" />
<img width="841" height="543" alt="06_média_de_dias_por_país" src="https://github.com/user-attachments/assets/799f10a7-a193-4d02-94e9-1a208c5ae7d0" />
<img width="609" height="505" alt="07_média_de_dias_por_região" src="https://github.com/user-attachments/assets/020753e4-5420-475e-8fbf-b8e4ee7565dc" />

### Evolução do lucro e da receita da empresa com o passar do tempo
<img width="846" height="491" alt="09_evolução_temporal_da_receita_e_lucro" src="https://github.com/user-attachments/assets/d800116b-87cf-47ce-abc6-dbcdcd3a826d" />

---

# Principais Insights

- A empresa apresenta em seu lucro uma oscilação ao longo do tempo, definida como uma sazonalidade de vendas.

- Em relação aos produtos da empresa, os materiais de escritório apresentam maior receita bruta, entretanto por um custo de produção alto, não são necessariamente os mais lucrativos.

- Os produtos com a maior margem de lucro são os cosméticos, sendo um bom foco de investimento para arrecadar lucro para a empresa.

- As vendas offline ainda são o canal mais utilizado na empresa, representando cerca de 51,2 % das vendas da empresa.

- Em relação aos países, ao analisar-se o escopo geral, o mais lucrativo se consta Andorra, um pequeno país da Europa. Apesar de ter uma população bem pouco numerosa, o alto lucro obtido pela empresa nesse país se explica pelo fato do país ter leis de compras com isenção de impostos. Já Mônaco, com a população sendo metade de Andorra, se trata do país menos lucrativo e também o com menos receita. Isso por ser na verdade um microestado soberano na Riviera Francesa, o que explica o baixo índice de compra da população.

- Em relação às regiões, a ásia apesar de haver uma maior média de tempo para entrega, é a região menos lucrativa para a empresa. Sendo assim uma opção menos favorável para a empresa, visto que apesar das entregas demorarem mais, se trata de uma região bem menos lucrativa se levar em conta a europa.

# Estrutura do Repositório

```text
product_sales_analysis
│
├── data
│   ├── countries.csv
│   ├── events.csv
│   └── products.csv
│
├── images
│   ├── 01_receita_por_categoria.png
│   ├── 02_receita_por_pais.png
│   ├── 03_receita_por_regiao.png
│   ├── 04_receita_por_canal_de_vendas.png
│   ├── 05_media_de_dias_por_categoria.png
│   ├── 06_media_de_dias_por_pais.png
│   ├── 07_media_de_dias_por_regiao.png
│   ├── 08_lucro_medio_por_faixa_de_tempo_de_entrega.png
│   ├── 09_evolucao_temporal_da_receita_e_lucro.png
│   ├── 10_receita_e_lucro_por_categoria.png
│   ├── 11_receita_e_lucro_por_pais.png
│   ├── 12_receita_e_lucro_por_regiao.png
│   └── 13_receita_e_lucro_por_dias.png
│
├── python
│   └── product_sales_analysis.ipynb
│
├── LICENSE
│
└── README.md
```

---

# Habilidades Demonstradas

- Python
- Data Cleaning
- Data Transformation
- Exploratory Data Analysis (EDA)
- Data Visualization
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Git
- GitHub

---

# Autor

Lailson de Menezes

[LinkedIn](https://www.linkedin.com/in/lailson-menezes-910908365/)

[GitHub](https://github.com/lailsonmenezes)
