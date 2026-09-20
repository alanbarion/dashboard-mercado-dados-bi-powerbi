# Dashboard de Mercado de Dados e BI no Brasil (Power BI)

Dashboard interativo desenvolvido em Power BI para analisar o mercado de trabalho em Dados e BI no Brasil, com base na pesquisa State of Data Brazil 2025-2026 (Data Hackers em parceria com a Bain & Company).

---

# Objetivo

Aplicar modelagem de dados, Power Query e DAX (medidas com `CALCULATE`, `ALLEXCEPT`, `AVERAGEX`, `MEDIANX` e `DIVIDE`) sobre uma pesquisa real do setor de Dados e BI, construindo um dashboard que analisa salários, ferramentas e perfil dos profissionais da área para a qual estou migrando.

---

## Tecnologias Utilizadas

| Ferramenta | Uso |
|---|---|
| Power BI Desktop | Modelagem, DAX e construção do dashboard |
| Power Query | Limpeza, transformação e modelagem dos dados |

---

# Fonte e Obtenção dos Dados

Os dados utilizados não estão incluídos neste repositório (dataset de terceiros, disponível publicamente no Kaggle).

1. Baixe o dataset original em: [State of Data Brazil 2025-2026 — Kaggle](https://www.kaggle.com/datasets/datahackers/state-of-data-brazil-2025-2026)
2. Abra o arquivo `.pbix` no Power BI Desktop e aponte a fonte de dados para o CSV baixado

A pesquisa contém **3.495 respondentes** no total. Após filtragem para profissionais atualmente empregados na área (removendo registros sem cargo, senioridade ou faixa salarial preenchidos), a análise considera **2.501 registros**.

---

# Estrutura do Projeto

dashboard-mercado-dados-bi-powerbi/
│
├── dashboard_mercado_dados_bi.pbix
├── screenshots/
│ ├── 01-visao-geral.png
│ ├── 02-salarios.png
│ ├── 03-ferramentas.png
│ └── 04-insight-pessoal.png
└── README.md



---

# Principais Análises e Insights

## 1. Progressão salarial por senioridade

O salário médio cresce de forma consistente com a senioridade: R$ 4.152 (Júnior) para R$ 14.469 (Sênior), chegando a R$ 20.028 em posições de Especialista/Staff+.

## 2. Cargo mais comum não é o mais bem pago

Analista de Dados é o cargo com mais respondentes (599 de 2.501), mas está na faixa inicial de salário. Cargos como Arquiteto de Dados e ML Engineer, mais raros, concentram os maiores salários médios.

## 3. Trabalho remoto paga significativamente mais

O salário médio de quem trabalha 100% remoto (R$ 13.470) é quase o dobro do modelo 100% presencial (R$ 6.645).

## 4. Adoção de ferramentas cresce com a senioridade

Python e SQL, as ferramentas mais usadas do mercado, têm adoção crescente por senioridade (Python: 69% entre Júniores, 80% entre Sêniores), indicando aprofundamento técnico contínuo ao longo da carreira.

## 5. Microsoft Power BI lidera as preferências de BI

Entre quem tem uma ferramenta de BI preferida, o Power BI domina com ampla margem sobre Tableau, Looker e demais concorrentes.

---

# Autor

**Alan Barion de Sá**
Analista de Dados Júnior | Business Intelligence | Dados Financeiros
📧 alanbarion@gmail.com 🔗 [LinkedIn](https://linkedin.com/in/alan-barion-de-sá-674a69284) 🐙 [GitHub](https://github.com/alanbarion)
