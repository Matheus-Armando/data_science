# Ciência de Dados - Trabalho de Faculdade

Repositório com os exercícios práticos da disciplina de Ciência de Dados, desenvolvidos em Python com Jupyter Notebook.

## Ambiente

- Python 3.12 (MSYS2)
- Jupyter Notebook
- pandas, numpy, matplotlib, xlrd

## Estrutura

```
data_science/
├── assignment1/
│   ├── data/
│   │   └── default_of_credit_card_clients__courseware_version_1_21_19.xls
│   ├── exercicio1_introducao_python.ipynb
│   └── exercicio2_carregando_dados.ipynb
├── assignment2/
│   ├── data/
│   │   └── default_of_credit_card_clients__courseware_version_1_21_19.xls
│   └── exercicio1_caracteristicas_financeiras.ipynb
└── README.md
```

## Assignment 1

### Exercício 1 - Introdução ao Python

**Arquivo:** `assignment1/exercicio1_introducao_python.ipynb`

Familiarização com o ambiente Anaconda e com a linguagem Python:

- Listagem de pacotes instalados com `conda list`
- Verificação da versão do Python
- Loop `for` com `range()`
- Estrutura de dados `dict`

### Exercício 2 - Carregando os Dados com pandas

**Arquivo:** `assignment1/exercicio2_carregando_dados.ipynb`

Carregamento e exploração inicial do dataset de inadimplência de cartão de crédito:

- Importação do pandas
- Leitura de arquivo Excel com `pd.read_excel()`
- Exploração dos dados: dimensões, tipos, estatísticas e valores faltantes

## Assignment 2

### Exercício 1 - Explorando as Características Financeiras

**Arquivo:** `assignment2/exercicio1_caracteristicas_financeiras.ipynb`

Análise das características financeiras do dataset com visualizações e transformações:

- Criação de listas com os nomes das características (`BILL_AMT1–6`, `PAY_AMT1–6`)
- Síntese estatística com `.describe()`
- Histogramas em grade 2x3 com matplotlib
- Identificação de pagamentos iguais a zero com máscara booleana
- Transformação logarítmica (`np.log10`) dos pagamentos diferentes de zero

## Dataset

`default_of_credit_card_clients__courseware_version_1_21_19.xls`

Dataset com dados demográficos e financeiros de 30.000 titulares de contas de cartão de crédito, rotulados de acordo com inadimplência no mês seguinte ao período histórico de seis meses.
