# Análise e Visualização de Dados — SINAN/Dengue 2026

Repositório de atividades práticas da disciplina **Introdução à Ciência de Dados**, do curso de Bacharelado em Sistemas de Informação do IFNMG — Campus Pirapora.

**Disciplina:** Introdução à Ciência de Dados  
**Professora:** Ana Palloma Rocha Fernandes  
**Base de dados:** SINAN/Dengue — 2026  
**Linguagem:** Python

---

## Sobre o projeto

Este repositório reúne atividades acadêmicas de análise de dados utilizando a base de notificações de dengue do Sistema de Informação de Agravos de Notificação (SINAN).

As atividades são desenvolvidas de forma progressiva, abordando a caracterização das variáveis, a análise exploratória, o pré-processamento de dados e a aplicação de técnicas de visualização.

O objetivo é praticar os conceitos estudados em sala, desenvolver habilidades de programação em Python e documentar cada etapa do processo de análise de dados.

## Fonte dos dados

Os dados utilizados são provenientes do Ministério da Saúde, por meio do Portal de Dados Abertos do SUS.

- **Conjunto de dados:** Sinan/Dengue.
- **Base utilizada:** Dengue — 2026.
- **Formato original:** CSV.
- **Abrangência temporal:** registros referentes a 2026.
- **Quantidade de registros e variáveis da versão utilizada na análise inicial:** 465.323 registros e 121 colunas.

Links oficiais:

- [Portal de Dados Abertos do SUS — Sinan/Dengue](https://dadosabertos.saude.gov.br/dataset/arboviroses-dengue)
- [Recurso oficial — Dengue 2026 (CSV)](https://dadosabertos.saude.gov.br/dataset/arboviroses-dengue/resource/f71ec0f9-82eb-4177-bd6a-ff76f2dfa84d)

O SINAN coleta, transmite e dissemina informações produzidas pela vigilância epidemiológica, apoiando a investigação e a análise de doenças e agravos de notificação compulsória.

**Importante:** a base pode receber atualizações. Por isso, a quantidade de registros e os resultados podem variar conforme a versão utilizada em cada atividade.

## Atividades desenvolvidas

### 1. Análise prévia do dataset — 29/09/2026

Atividade voltada ao reconhecimento e à caracterização inicial da base de dados.

Principais etapas:

- Identificação da quantidade de registros e variáveis.
- Exploração dos dados com Pandas.
- Classificação das variáveis de acordo com suas características.
- Identificação de variáveis nominais, ordinais, discretas e temporais.
- Consulta ao dicionário de dados do SINAN/Dengue.

Notebook: `Analise_SINAN_Dengue_Atividade_29-09-2026.ipynb`

### 2. Pré-processamento de dados com POO 13/10/2026

Atividade dedicada à organização e ao pré-processamento da base, utilizando conceitos de Programação Orientada a Objetos (POO).

A proposta é aplicar os conceitos estudados em aula para estruturar o código e preparar os dados para análises posteriores.

Notebook: `pre_processamento_SINAN_Dengue_POO.ipynb`

### 3. Visualização avançada de dados — 21/10/2026

Atividade prática destinada à aplicação de técnicas de visualização de dados estudadas em sala de aula, utilizando a base SINAN/Dengue 2026.

Técnicas desenvolvidas:

- **Gráfico de barras:** comparação da quantidade de notificações por semana epidemiológica.
- **Histograma:** visualização da distribuição dos registros por ano de nascimento.
- **Boxplot:** análise da distribuição dos anos de nascimento e identificação de possíveis valores extremos.
- **Gráfico de dispersão (*Scatter Plot*):** exploração da distribuição dos registros conforme o ano de nascimento e a semana epidemiológica da notificação.
- **Mapa de calor (*Heatmap*):** visualização da correlação entre os códigos das variáveis relacionadas aos sintomas.
- **Dashboard:** organização de quatro gráficos em um único painel.
- **Gráfico interativo com Plotly:** exploração interativa dos registros por meio de uma visualização de dispersão.

As visualizações são utilizadas para explorar os dados, observar distribuições e identificar padrões que possam orientar análises posteriores.

**Notebook:** `Visualização_Avançada_de_Dados_SINAN_Dengue_2026_Atividade_21_10_2026.ipynb`

**Google Colab:** [Inserir aqui o link compartilhável do notebook]

## Tecnologias e ferramentas utilizadas

- **Python:** linguagem de programação utilizada nas atividades.
- **Google Colab:** ambiente para execução dos notebooks.
- **Pandas:** carregamento, organização e manipulação dos dados.
- **NumPy:** suporte a operações numéricas.
- **Matplotlib:** construção de gráficos e visualizações.
- **Seaborn:** visualizações estatísticas, como boxplots e mapas de calor.
- **Plotly Express:** construção de gráficos interativos.
- **GitHub:** armazenamento, versionamento e documentação dos arquivos do projeto.

## Organização do repositório

A estrutura abaixo representa a organização proposta para o projeto. Os nomes dos arquivos e das pastas devem corresponder aos existentes no GitHub.

```text
Introducao_a_ciencia_de_dados/
│
├── dados/
│   └── DENGBR26.csv
│
├── notebooks/
│   ├── Analise_SINAN_Dengue_Atividade_29-09-2026.ipynb
│   ├── pre_processamento_SINAN_Dengue_POO.ipynb
│   └── Visualização_Avançada_de_Dados_SINAN_Dengue_2026_Atividade_21_10_2026.ipynb
│
├── dicionario_variaveis/
│
└── README.md
```

## Observações sobre a análise

- Os dados são utilizados para fins acadêmicos e de aprendizagem.
- As notificações presentes na base representam registros do sistema e não devem ser interpretadas automaticamente como indivíduos únicos ou casos confirmados.
- Variáveis numéricas podem representar códigos categóricos, identificadores ou datas codificadas. Sua interpretação depende do dicionário de dados.
- A correlação entre variáveis não demonstra, por si só, causalidade.
- A identificação de possíveis valores extremos não significa necessariamente que existam erros nos registros.
- Os resultados dependem da versão da base utilizada e dos procedimentos aplicados em cada atividade.

## Referências

BRASIL. Ministério da Saúde. **Portal de Dados Abertos do SUS: Sinan/Dengue**. Brasília, DF: Ministério da Saúde. Disponível em: https://dadosabertos.saude.gov.br/dataset/arboviroses-dengue. Acesso em: 27 out. 2026.

BRASIL. Ministério da Saúde. **Dengue — Base de dados de 2026**. Portal de Dados Abertos do SUS. Disponível em: https://dadosabertos.saude.gov.br/dataset/arboviroses-dengue/resource/f71ec0f9-82eb-4177-bd6a-ff76f2dfa84d. Acesso em: 27 out. 2026.
