# 🐍 Atividades de Python — COTEMIG

Repositório com as atividades de Python feitas nas aulas do **COTEMIG**, com foco em **análise de dados**.

Os exercícios usam dados públicos reais (IBGE, PNAD, IDHM). Em cada um eu leio, limpo, transformo, analiso e visualizo tabelas com Python e Jupyter Notebook.

## 📚 Atividades

| # | Atividade | Assuntos |
|---|---|---|
| 01 | [NumPy: arrays e matrizes](01-numpy-arrays-e-matrizes) | `array`, `mean`, `ndim`, `shape` |
| 02 | [Indicador de afazeres domésticos (IBGE)](02-pandas-indicador-mulheres-ibge) | leitura de `.xls`, limpeza de dados, filtros, cálculo de percentuais |
| 03 | [Áreas de formação na graduação (IBGE)](03-pandas-areas-formacao-graduacao) | divisão de tabelas, `describe()`, exportação para `.xlsx` |
| 04 | [População 2010 × 2022 (Censo)](04-pandas-populacao-censo-2022) | `groupby`, `sum`, ordenação, exportação para `.csv` |
| 05 | [Evolução do IDHM por estado](05-matplotlib-idhm-estados) | CSV com vírgula decimal, `melt`, gráficos de linha com matplotlib |
| 06 | [Desocupação por sexo × afazeres domésticos](06-seaborn-desocupacao-afazeres) | `merge`, `melt`, gráficos de barras com seaborn, correlação |

## 🛠️ Tecnologias

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)

## 📁 Organização

Cada atividade fica em uma pasta numerada com:
- o notebook (`.ipynb`) com o código e as respostas
- os arquivos de dados usados
- as tabelas e os gráficos gerados
- um `README.md` explicando a atividade

## 🚀 Como executar

1. Clone o repositório:
```bash
   git clone https://github.com/SEU-USUARIO/NOME-DO-REPO.git
   cd NOME-DO-REPO
```
2. Instale as dependências:
```bash
   pip install numpy pandas matplotlib seaborn xlrd openpyxl notebook
```
3. Abra o Jupyter e escolha a atividade:
```bash
   jupyter notebook
```

> Os notebooks usam caminhos relativos, então é só abrir o notebook de dentro da própria pasta da atividade.

## 📊 Fontes dos dados

- [IBGE](https://www.ibge.gov.br/): Censo Demográfico, Estatísticas de Gênero, PNAD Contínua
- [Atlas do Desenvolvimento Humano no Brasil](http://www.atlasbrasil.org.br/): IDHM


[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/SEU-PERFIL)
