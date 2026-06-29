# MiniProjeto DataView

## Sobre o Projeto

O DataView é um projeto de Análise Exploratória de Dados (EDA) desenvolvido em Python utilizando Jupyter Notebook.

O sistema gera um dataset sintético de vendas, realiza a limpeza dos dados, tratamento de outliers, criação de variáveis derivadas, cálculo de métricas, segmentação de clientes, geração de visualizações e exportação dos resultados.

O objetivo é demonstrar a aplicação prática dos principais conceitos estudados no módulo de Python para Ciência de Dados.

---

## Objetivo

Praticar e demonstrar conhecimentos em:

- Lógica de programação
- Estruturas condicionais
- Estruturas de repetição
- Funções com parâmetros e retorno
- Funções lambda
- Funções reutilizáveis
- Expressões regulares (Regex)
- Manipulação de datas com datetime
- Manipulação de arquivos CSV e JSON
- Pandas para análise de dados
- NumPy para cálculos vetorizados
- Detecção e tratamento de outliers
- Visualização de dados com Matplotlib e Seaborn
- Organização de projetos de análise de dados
- Versionamento com Git e GitHub

---

## Dataset

O dataset foi gerado sinteticamente através de código Python para fins educacionais.

Cada registro representa uma venda contendo as seguintes informações:

| Coluna | Descrição |
|----------|----------|
| id_venda | Identificador da venda |
| data_venda | Data da venda |
| cliente | Cliente responsável pela compra |
| produto | Produto vendido |
| categoria | Categoria do produto |
| regiao | Região da venda |
| quantidade | Quantidade vendida |
| preco_unitario | Preço unitário |

O dataset foi criado propositalmente contendo problemas comuns encontrados em dados reais:

- Valores nulos
- Datas inválidas
- Espaços extras em textos
- Outliers

---

## Estrutura do Projeto

```text
projeto/
│
├── data/
│   ├── raw/
│   ├── processed/
│   │   ├── v1_com_outliers/
│   │   └── v2_outliers_tratado/
│   └── final/
│
├── notebooks/
│   └── dataview.ipynb
│
├── outputs/
│   ├── graficos/
│   ├── metricas_por_mes.csv
│   ├── segmentacao_clientes.csv
│   └── estatisticas_gerais.json
│
├── README.md
└── requirements.txt
```

## Dataset Final Escolhido

Foi utilizada a versão:

**v2_outliers_tratado**

para a geração do dataset final e das análises.

## Ferramentas Utilizadas

- Python 3.12
- VS Code
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- datetime
- re
- json
- os
- Git
- GitHub

## Repositório GitHub

Inserir link do repositório público.

## Vídeo de Demonstração

Inserir link do vídeo (YouTube ou Google Drive).
