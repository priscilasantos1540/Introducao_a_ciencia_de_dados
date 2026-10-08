# Introducao_a_ciencia_de_dados
Atividade 29/09/2026
Matéria: Introdução a Ciência de dados
Profª Ana Palloma Rocha Fernandes
Atividade Prática: Análise prévia de dataset
Requisitos da análise
### O que é o dataset?

O dataset utilizado neste trabalho é uma base de dados do **Sistema de
Informação de Agravos de Notificação (SINAN)**, referente às notificações
de dengue.

A base possui **465.323 instâncias**, correspondentes aos registros de
notificações, e **121 características**, que representam os campos
disponíveis na ficha de notificação.

As características apresentam diferentes naturezas estatísticas,
podendo ser classificadas como nominais, ordinais, discretas e
contínuas, de acordo com o significado e as categorias definidas no
Dicionário de Dados do SINAN Dengue.

As variáveis nominais representam categorias sem ordem natural, como
sexo, UF e município. As variáveis ordinais apresentam categorias que
possuem uma ordem, como escolaridade. As variáveis discretas
representam valores contáveis ou inteiros, como semana e ano. As
variáveis contínuas representam informações em escala temporal, como
as datas registradas na notificação.

### Classificação das características

As características do dataset foram classificadas de acordo com
o significado das variáveis apresentado no Dicionário de Dados
do **SINAN** Dengue.

**A classificação considera quatro tipos:**

- Nominais: representam categorias sem ordem natural.
- Ordinais: representam categorias que possuem uma ordem natural.
- Discretas: representam valores contáveis ou inteiros.
- Contínuas: representam medidas em uma escala contínua. Neste dataset,
  as variáveis temporais (datas) foram consideradas como variáveis contínuas
  de natureza temporal.


### Dicionário das 121 características do banco de dados SINAN – Dengue

| Nº | Característica | Descrição | Tipo de variável |
|---:|---|---|---|
| 1 | `TP_NOT` | Tipo de notificação | Nominal |
| 2 | `ID_AGRAVO` | Código do agravo notificado | Nominal |
| 3 | `DT_NOTIFIC` | Data da notificação | Temporal |
| 4 | `SEM_NOT` | Semana epidemiológica da notificação | Discreta |
| 5 | `NU_ANO` | Ano da notificação | Discreta |
| 6 | `SG_UF_NOT` | Unidade federativa da notificação | Nominal |
| 7 | `ID_MUNICIP` | Código do município da notificação | Nominal |
| 8 | `ID_REGIONA` | Código da região de saúde da notificação | Nominal |
| 9 | `ID_UNIDADE` | Código da unidade de saúde notificadora | Nominal |
| 10 | `DT_SIN_PRI` | Data dos primeiros sintomas | Temporal |
| 11 | `SEM_PRI` | Semana epidemiológica dos primeiros sintomas | Discreta |
| 12 | `ANO_NASC` | Ano de nascimento do paciente | Discreta |
| 13 | `NU_IDADE_N` | Idade codificada do paciente | Discreta codificada |
| 14 | `CS_SEXO` | Sexo do paciente | Nominal |
| 15 | `CS_GESTANT` | Situação gestacional | Nominal |
| 16 | `CS_RACA` | Raça ou cor declarada | Nominal |
| 17 | `CS_ESCOL_N` | Escolaridade do paciente | Ordinal |
| 18 | `SG_UF` | Unidade federativa de residência | Nominal |
| 19 | `ID_MN_RESI` | Código do município de residência | Nominal |
| 20 | `ID_RG_RESI` | Código da região de saúde de residência | Nominal |
| 21 | `ID_PAIS` | Código do país de residência | Nominal |
| 22 | `DT_INVEST` | Data de início da investigação | Temporal |
| 23 | `ID_OCUPA_N` | Código da ocupação do paciente | Nominal |
| 24 | `FEBRE` | Presença de febre | Nominal |
| 25 | `MIALGIA` | Presença de mialgia | Nominal |
| 26 | `CEFALEIA` | Presença de cefaleia | Nominal |
| 27 | `EXANTEMA` | Presença de exantema | Nominal |
| 28 | `VOMITO` | Presença de vômito | Nominal |
| 29 | `NAUSEA` | Presença de náusea | Nominal |
| 30 | `DOR_COSTAS` | Presença de dor nas costas | Nominal |
| 31 | `CONJUNTVIT` | Presença de conjuntivite | Nominal |
| 32 | `ARTRITE` | Presença de artrite | Nominal |
| 33 | `ARTRALGIA` | Presença de artralgia | Nominal |
| 34 | `PETEQUIA_N` | Presença de petéquias | Nominal |
| 35 | `LEUCOPENIA` | Presença de leucopenia | Nominal |
| 36 | `LACO` | Resultado da prova do laço | Nominal |
| 37 | `DOR_RETRO` | Presença de dor retro-orbitária | Nominal |
| 38 | `DIABETES` | Presença de diabetes | Nominal |
| 39 | `HEMATOLOG` | Presença de doença hematológica | Nominal |
| 40 | `HEPATOPAT` | Presença de hepatopatia | Nominal |
| 41 | `RENAL` | Presença de doença renal | Nominal |
| 42 | `HIPERTENSA` | Presença de hipertensão | Nominal |
| 43 | `ACIDO_PEPT` | Presença de doença ácido-péptica | Nominal |
| 44 | `AUTO_IMUNE` | Presença de doença autoimune | Nominal |
| 45 | `DT_CHIK_S1` | Data da primeira coleta para exame de chikungunya | Temporal |
| 46 | `DT_CHIK_S2` | Data da segunda coleta para exame de chikungunya | Temporal |
| 47 | `DT_PRNT` | Data de coleta para exame PRNT | Temporal |
| 48 | `RES_CHIKS1` | Resultado da primeira sorologia para chikungunya | Nominal |
| 49 | `RES_CHIKS2` | Resultado da segunda sorologia para chikungunya | Nominal |
| 50 | `RESUL_PRNT` | Resultado do exame PRNT | Nominal |
| 51 | `DT_SORO` | Data da coleta para sorologia de dengue | Temporal |
| 52 | `RESUL_SORO` | Resultado da sorologia | Nominal |
| 53 | `DT_NS1` | Data da coleta do exame NS1 | Temporal |
| 54 | `RESUL_NS1` | Resultado do exame NS1 | Nominal |
| 55 | `DT_VIRAL` | Data da coleta para isolamento viral | Temporal |
| 56 | `RESUL_VI_N` | Resultado do isolamento viral | Nominal |
| 57 | `DT_PCR` | Data da coleta para exame PCR | Temporal |
| 58 | `RESUL_PCR_` | Resultado do exame PCR | Nominal |
| 59 | `SOROTIPO` | Sorotipo identificado do vírus da dengue | Nominal |
| 60 | `HISTOPA_N` | Resultado do exame histopatológico | Nominal |
| 61 | `IMUNOH_N` | Resultado do exame de imuno-histoquímica | Nominal |
| 62 | `HOSPITALIZ` | Indicação de hospitalização | Nominal |
| 63 | `DT_INTERNA` | Data da internação | Temporal |
| 64 | `UF` | Unidade federativa relacionada à internação | Nominal |
| 65 | `MUNICIPIO` | Município relacionado à internação | Nominal |
| 66 | `TPAUTOCTO` | Indicação de caso autóctone do município de residência | Nominal |
| 67 | `COUFINF` | Unidade federativa provável de infecção | Nominal |
| 68 | `COPAISINF` | País provável de infecção | Nominal |
| 69 | `COMUNINF` | Município provável de infecção | Nominal |
| 70 | `CLASSI_FIN` | Classificação final do caso | Nominal |
| 71 | `CRITERIO` | Critério de confirmação do caso | Nominal |
| 72 | `DOENCA_TRA` | Indicação de doença relacionada ao trabalho | Nominal |
| 73 | `CLINIC_CHIK` | Classificação clínica de chikungunya | Nominal |
| 74 | `EVOLUCAO` | Evolução do caso | Nominal |
| 75 | `DT_OBITO` | Data do óbito | Temporal |
| 76 | `DT_ENCERRA` | Data do encerramento da investigação | Temporal |
| 77 | `ALRM_HIPOT` | Sinal de alarme: hipotensão postural | Nominal |
| 78 | `ALRM_PLAQ` | Sinal de alarme: queda de plaquetas | Nominal |
| 79 | `ALRM_VOM` | Sinal de alarme: vômitos persistentes | Nominal |
| 80 | `ALRM_SANG` | Sinal de alarme: sangramento de mucosas | Nominal |
| 81 | `ALRM_HEMAT` | Sinal de alarme: hematócrito elevado | Nominal |
| 82 | `ALRM_ABDOM` | Sinal de alarme: dor abdominal intensa | Nominal |
| 83 | `ALRM_LETAR` | Sinal de alarme: letargia ou irritabilidade | Nominal |
| 84 | `ALRM_HEPAT` | Sinal de alarme: aumento do fígado | Nominal |
| 85 | `ALRM_LIQ` | Sinal de alarme: acúmulo de líquidos | Nominal |
| 86 | `DT_ALRM` | Data de identificação dos sinais de alarme | Temporal |
| 87 | `GRAV_PULSO` | Sinal de gravidade: pulso débil ou indetectável | Nominal |
| 88 | `GRAV_CONV` | Sinal de gravidade: comprometimento da consciência | Nominal |
| 89 | `GRAV_ENCH` | Sinal de gravidade: tempo de enchimento capilar prolongado | Nominal |
| 90 | `GRAV_INSUF` | Sinal de gravidade: insuficiência respiratória | Nominal |
| 91 | `GRAV_TAQUI` | Sinal de gravidade: taquicardia | Nominal |
| 92 | `GRAV_EXTRE` | Sinal de gravidade: extremidades frias | Nominal |
| 93 | `GRAV_HIPOT` | Sinal de gravidade: hipotensão arterial | Nominal |
| 94 | `GRAV_HEMAT` | Sinal de gravidade: hematócrito elevado associado a choque | Nominal |
| 95 | `GRAV_MELEN` | Sinal de gravidade: melena | Nominal |
| 96 | `GRAV_METRO` | Sinal de gravidade: metrorragia | Nominal |
| 97 | `GRAV_SANG` | Sinal de gravidade: hemorragia grave | Nominal |
| 98 | `GRAV_AST` | Sinal de gravidade: aumento de AST/ALT | Nominal |
| 99 | `GRAV_MIOC` | Sinal de gravidade: miocardite | Nominal |
| 100 | `GRAV_CONSC` | Sinal de gravidade: alteração da consciência | Nominal |
| 101 | `GRAV_ORGAO` | Sinal de gravidade: comprometimento grave de órgãos | Nominal |
| 102 | `DT_GRAV` | Data de identificação da gravidade | Temporal |
| 103 | `MANI_HEMOR` | Manifestação hemorrágica | Nominal |
| 104 | `EPISTAXE` | Presença de epistaxe | Nominal |
| 105 | `GENGIVO` | Presença de sangramento gengival | Nominal |
| 106 | `METRO` | Presença de metrorragia | Nominal |
| 107 | `PETEQUIAS` | Presença de petéquias | Nominal |
| 108 | `HEMATURA` | Presença de hematúria | Nominal |
| 109 | `SANGRAM` | Presença de outras manifestações hemorrágicas | Nominal |
| 110 | `LACO_N` | Resultado da prova do laço | Nominal |
| 111 | `PLASMATICO` | Evidência de extravasamento plasmático | Nominal |
| 112 | `EVIDENCIA` | Evidência de dengue grave | Nominal |
| 113 | `PLAQ_MENOR` | Contagem de plaquetas abaixo do limite indicado | Nominal |
| 114 | `CON_FHD` | Critérios compatíveis com febre hemorrágica da dengue | Nominal |
| 115 | `COMPLICA` | Complicações do caso | Nominal |
| 116 | `TP_SISTEMA` | Sistema de origem do registro | Nominal |
| 117 | `NDUPLIC_N` | Indicador de duplicidade da notificação | Nominal |
| 118 | `DT_DIGITA` | Data de digitação do registro | Temporal |
| 119 | `CS_FLXRET` | Situação do registro no fluxo de retorno | Nominal |
| 120 | `FLXRECEBI` | Informação de recebimento pelo fluxo de retorno | Nominal |
| 121 | `MIGRADO_W` | Indicador de migração do registro do Sinan Windows | Nominal |


**Resumo da classificação:**

As características do conjunto de dados são predominantemente nominais, incluindo variáveis categóricas e códigos de identificação. Também estão presentes características ordinais, discretas e temporais, como as relacionadas à escolaridade, idade, semanas epidemiológicas e datas dos registros. Não foram identificadas características quantitativas contínuas entre as variáveis analisadas.


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

## Tecnologias utilizadas

- **Python** — linguagem de programação utilizada na análise dos dados.
- **Google Colab** — ambiente para executar os códigos e documentar a análise.
- **Pandas** — carregamento, organização e manipulação dos dados.
- **NumPy** — suporte a operações numéricas e computacionais.
- **Matplotlib** — criação de gráficos básicos e visualizações.
- **Seaborn** — criação de gráficos estatísticos e análise exploratória.
- **Plotly Express** — criação de gráficos interativos.
- **GitHub** — armazenamento, versionamento e compartilhamento do projeto.
- **SINAN/DATASUS — Dados Abertos do Ministério da Saúde** — fonte dos dados de dengue utilizados no projeto.

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
