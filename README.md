# DataView: Análise Preditiva e Exploratória de Vendas

## Visão Geral do Projeto

O **DataView** é um pipeline completo de análise de dados desenvolvido em Python com foco em práticas de **Data Science e Análise Preditiva aplicada a negócios**.

O projeto simula um cenário real de uma empresa de varejo que precisa entender seu desempenho de vendas para apoiar decisões estratégicas da diretoria.

Ao longo do pipeline, os dados passam por etapas de:
- geração sintética com inconsistências
- limpeza e tratamento
- transformação e engenharia de atributos
- análise exploratória e estatística
- segmentação de clientes
- visualização de dados
- exportação de relatórios

---

## Objetivos de Negócio

O time de negócio deseja responder às seguintes perguntas:

- Como as vendas evoluem ao longo do tempo (mensal e trimestral)?
- Quais produtos e categorias geram maior receita?
- Quais regiões apresentam melhor desempenho?
- Quem são os clientes mais valiosos?
- Existe concentração de receita em poucos clientes (efeito Pareto)?

---

## Estrutura do Projeto

projeto/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── final/
│
├── notebooks/
│   └── 01_analise_exploratoria_vendas.ipynb
│
├── outputs/
│   ├── graficos/
│   ├── metricas_por_mes.csv
│   ├── segmentacao_clientes.csv
│   └── estatisticas_gerais.json
│
├── README.md
└── requirements.txt

---

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Regex

---

## Pipeline de Dados

1. Geração do Dataset (RF01)
2. Inspeção de Dados (RF02)
3. Limpeza e Tratamento (RF03)
4. Outliers (RF04)
5. Engenharia de Atributos (RF05)
6. Métricas de Negócio (RF06)
7. Segmentação de Clientes (RF07)
8. Estatísticas Numéricas (RF08)
9. Visualização de Dados (RF09)
10. Organização em Funções (RF10)
11. Exportação de Dados (RF11)

---

## Principais Insights

- Variação significativa de receita ao longo do ano
- Produtos líderes: Tablets e Smartphones
- Categoria dominante: Celulares
- Região Norte com maior receita total
- Forte concentração de receita em poucos clientes

---

## Segmentação de Clientes

- Ouro: clientes de alto valor
- Prata: clientes intermediários
- Bronze: clientes ocasionais

---

## Como Executar

pip install pandas numpy matplotlib seaborn

Execute o notebook:
01_analise_exploratoria_vendas.ipynb

---

## Conclusão

Pipeline completo de análise de dados com foco em varejo, cobrindo desde dados brutos até insights estratégicos.

---

## Melhorias futuras

- Modelos preditivos
- Clustering de clientes
- Dashboard interativo
