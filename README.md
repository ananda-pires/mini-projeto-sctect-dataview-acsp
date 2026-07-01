# DataView: Análise Exploratória e Preditiva de Vendas

## Sobre o Projeto

O **DataView** é um projeto de análise exploratória de dados (EDA) desenvolvido em **Python**, utilizando um pipeline completo de processamento de dados baseado no processo **ETL (Extract, Transform and Load)**.

O projeto simula um cenário real de uma empresa de varejo que necessita transformar dados brutos de vendas em informações estratégicas para apoiar a tomada de decisão.

Durante o desenvolvimento são aplicadas técnicas de geração de dados, limpeza, transformação, análise estatística, visualização e exportação de resultados, seguindo boas práticas de organização e reutilização de código.

---

# Objetivos do Projeto

Responder perguntas importantes para o negócio, como:

- Como as vendas evoluem ao longo dos meses e trimestres?
- Quais produtos e categorias geram maior receita?
- Quais regiões apresentam melhor desempenho?
- Quem são os clientes mais valiosos?
- Existe concentração de receita em poucos clientes (Princípio de Pareto)?
- Como o tratamento de outliers influencia as análises?

---

# O que o projeto analisa

✔ Receita total por mês

✔ Receita por trimestre

✔ Produtos mais vendidos

✔ Categorias mais rentáveis

✔ Receita por região

✔ Ticket médio

✔ Segmentação de clientes (Bronze, Prata e Ouro)

✔ Estatísticas descritivas

✔ Comparação entre dados com e sem tratamento de outliers

✔ Exportação automática de relatórios

---

# Conceitos Aplicados

Durante o desenvolvimento foram utilizados diversos conceitos de programação e análise de dados, incluindo:

- Variáveis e tipos de dados
- Operadores aritméticos e lógicos
- Estruturas condicionais (`if`, `elif`, `else`)
- Estruturas de repetição (`for` e `while`)
- Funções reutilizáveis
- Funções Lambda
- Manipulação de arquivos CSV e JSON
- Manipulação de datas com `datetime`
- Expressões regulares (`re`)
- Organização modular do código
- Tratamento de exceções
- Programação orientada à reutilização

---

# Bibliotecas Utilizadas

- Python 3.10+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- datetime
- re
- os
- random

---

# Pipeline do Projeto

O projeto foi desenvolvido em etapas organizadas:

### RF01
Geração do dataset sintético de vendas.

### RF02
Inspeção inicial dos dados.

### RF03
Limpeza e tratamento dos dados.

### RF04
Identificação e tratamento de outliers utilizando IQR.

### RF05
Engenharia de atributos.

### RF06
Cálculo de indicadores de negócio.

### RF07
Segmentação de clientes.

### RF08
Análise estatística descritiva.

### RF09
Visualizações com Matplotlib e Seaborn.

### RF10
Refatoração e organização em funções reutilizáveis.

### RF11
Exportação de arquivos CSV, JSON e gráficos.

---

# Estrutura do Projeto

```
DataView/
│
├── data/
│   ├── raw/
│   │   └── vendas.csv
│   │
│   ├── processed/
│   │   ├── v1_com_outliers/
│   │   └── v2_outliers_tratado/
│   │
│   └── final/
│
├── notebooks/
│   └── 01_analise_exploratoria_vendas.ipynb
│
├── outputs/
│   ├── graficos/
│   ├── metricas_por_mes.csv
│   ├── segmentacao_clientes.csv
│   ├── estatisticas_gerais.json
│   └── comparativo_outliers.csv
│
├── requirements.txt
└── README.md
```

---

# Visualizações Geradas

O projeto gera automaticamente gráficos como:

- Receita por mês
- Receita por trimestre
- Receita por categoria
- Receita por região
- Top produtos
- Distribuição da receita
- Boxplot antes e depois do tratamento de outliers
- Segmentação de clientes

Todos os gráficos são exportados em formato PNG para a pasta `outputs/graficos`.

---

# Arquivos Exportados

Ao final da execução são gerados automaticamente:

- `metricas_por_mes.csv`
- `segmentacao_clientes.csv`
- `estatisticas_gerais.json`
- gráficos em PNG

---

# Como Executar

## 1. Clone o repositório

```bash
git clone https://github.com/ananda-pires/mini-projeto-sctect-dataview-acsp.git
```

## 2. Entre na pasta

```bash
cd DataView
```

## 3. Instale as dependências

```bash
pip install pandas numpy matplotlib seaborn
```

## 4. Execute o notebook

Abra o arquivo:

```
notebooks/01_analise_exploratoria_vendas.ipynb
```

e execute todas as células em ordem.

---

# Principais Insights Obtidos

- Forte variação da receita ao longo do período analisado.
- Produtos da categoria **Celulares** apresentam maior faturamento.
- A região com maior receita total foi a **Norte**.
- Pequena parcela dos clientes concentra grande parte da receita (Princípio de Pareto).
- O tratamento de outliers reduziu a dispersão dos dados sem alterar significativamente os indicadores de negócio.

---

# Melhorias Futuras

- Dashboard interativo com Streamlit
- Modelos preditivos de vendas
- Clusterização de clientes
- Previsão de demanda
- Deploy da aplicação
- Integração com banco de dados

---

# Desenvolvido com

- Python
- VS Code
- Git
- GitHub
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# Vídeo de Demonstração

> Inserir o link do vídeo (YouTube ou Google Drive).

---

# Licença

Projeto desenvolvido para fins educacionais no curso de Análise de Dados.