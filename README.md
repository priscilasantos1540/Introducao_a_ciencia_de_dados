# Introducao_a_ciencia_de_dados
Atividade 29/09/2026
Atividade Prática: Análise prévia de dataset
Requisitos da análise
1. O que é o dataset?
2. Número de instâncias.
3. Números de características.
4. Tipos de cada característica (nominais, oridinais,continuas, discretas).

Sugestões e Observações
Sugestão de fontes: Dados do IBGE, DATASUS, INEP, IPEAdata, entre outros.
Observação: Escolher com carinho e critério para o uso contínuo nas aulas.

# Base de dados escolhida
# SINAN/Dengue 2026 — Ministério da Saúde PNS 2019 - Pesquisa Nacional de Saúde

# Análise de Dados — SINAN/Dengue 2026

## Sobre o projeto

Este projeto apresenta uma análise exploratória da base de dados de **Dengue do Sistema de Informação de Agravos de Notificação (SINAN)**, disponibilizada pelo **Ministério da Saúde**, por meio do Portal de Dados Abertos do SUS.

A análise foi desenvolvida como atividade acadêmica da disciplina de **Ciência de Dados**, utilizando técnicas de exploração, identificação e caracterização das variáveis presentes no conjunto de dados.

## 🗂️ Fonte dos dados

**Fonte oficial:** Ministério da Saúde — Portal de Dados Abertos do SUS

**Conjunto de dados:** Sinan/Dengue

**Base utilizada:** Dengue – 2026

**Formato:** CSV

**Período:** 2026

**Data da última atualização da base:** 06/10/2026

🔗 [Portal de Dados Abertos do SUS — Sinan/Dengue](https://dadosabertos.saude.gov.br/dataset/arboviroses-dengue)

🔗 [Base Dengue — 2026](https://dadosabertos.saude.gov.br/dataset/arboviroses-dengue/resource/f71ec0f9-82eb-4177-bd6a-ff76f2dfa84d)

## Sobre o SINAN

O Sistema de Informação de Agravos de Notificação (SINAN) tem como finalidade coletar, transmitir e disseminar dados gerados pela vigilância epidemiológica, contribuindo para a investigação e análise de doenças e agravos de notificação compulsória.

A dengue é uma doença de notificação compulsória, portanto os casos suspeitos e/ou confirmados devem ser registrados no sistema de vigilância epidemiológica.

## Objetivo da análise

O objetivo desta atividade é conhecer e caracterizar o conjunto de dados utilizado, identificando:

- número de registros (instâncias);
- número de variáveis (características);
- tipos das variáveis;
- características qualitativas e quantitativas;
- variáveis nominais, ordinais, discretas e contínuas;
- possíveis valores ausentes ou inconsistentes;
- informações relevantes para futuras etapas de análise exploratória.

## Tecnologias utilizadas

- Python
- Google Colab
- Pandas
- NumPy
- GitHub

## Organização do projeto

```text
SINAN-Dengue-2026/
│
├── dados/
│   └── base_dengue_2026.csv
│
├── notebooks/
│   └── Analise_SINAN_Dengue_Atividade_29-09-2026.ipynb
│
├── README.md
│
└── dicionario_variaveis/
```

## Observações:

Os dados utilizados são provenientes de uma fonte pública oficial do Ministério da Saúde. A base pode sofrer atualizações ao longo do tempo. Por esse motivo, os resultados obtidos na análise estão relacionados à versão da base utilizada no desenvolvimento da atividade.

A utilização dos dados neste projeto tem finalidade exclusivamente acadêmica.

## Referência

MINISTÉRIO DA SAÚDE. **Portal de Dados Abertos do SUS — Sinan/Dengue**. Brasília: Ministério da Saúde. Disponível no Portal de Dados Abertos do SUS. Acesso em: 08 out. 2026.
