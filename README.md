# Analise-Consumo-Energia
Analisar a evolução do consumo de energia elétrica por tipo de fonte
# README

## 📊 Visão Geral
Este projeto tem como objetivo explorar dados públicos sobre o consumo de energia no Brasil, com foco na transição energética rumo a fontes renováveis. Utilizamos Python, bibliotecas de análise de dados e ferramentas de visualização para gerar insights relevantes sobre sustentabilidade no setor elétrico brasileiro.

## 🎯 Objetivos do Projeto
- Analisar a evolução do consumo de energia por fonte (hidrelétrica, solar, eólica, térmica etc).
- Comparar os estados brasileiros quanto ao uso de fontes renováveis.
- Identificar tendências de crescimento de energias limpas.
- Criar dashboards interativos para visualização dos dados.

## 🧰 Tecnologias Utilizadas
- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook
- Power BI ou Tableau (visualização interativa)
- Git e GitHub

## 📁 Estrutura de Pastas
```
analise-consumo-energia-sustentavel/
├── dados/                  # Conjunto de dados brutos e tratados
├── notebooks/              # Notebooks Jupyter com análises
├── src/                    # Scripts Python para limpeza e preparação dos dados
├── dashboards/             # Painéis interativos (Power BI ou Tableau)
├── relatorio_final.pdf     # Relatório com insights principais
└── README.md               # Documentação do projeto
```

## 🔎 Fontes de Dados
- [ANEEL - Agência Nacional de Energia Elétrica](https://www.aneel.gov.br/)
- [ONS - Operador Nacional do Sistema Elétrico](https://www.ons.org.br/)
- [IBGE - Instituto Brasileiro de Geografia e Estatística](https://www.ibge.gov.br/)
- [Dados Abertos - Governo Federal](https://dados.gov.br/)

## 🚀 Etapas do Projeto
1. Coleta de dados
2. Limpeza e tratamento
3. Análise exploratória (EDA)
4. Visualização interativa (Power BI/Tableau)
5. Conclusões e recomendações

## 👨‍💻 Autor
Felipe Naliato – Projeto de portfólio para transição de carreira para Análise de Dados.

---

## ⚡ Em andamento...
Nas próximas etapas, carregaremos os dados reais e iniciaremos a exploração no notebook `exploracao_dados.ipynb`.

---

# Etapas do Projeto:
# 1. Coleta de dados públicos (ANEEL, ONS, IBGE)
# 2. Limpeza e tratamento dos dados
# 3. Análise exploratória e visualização (Pandas, Seaborn)
# 4. Painel interativo com Power BI ou Tableau (fora do notebook)
# 5. Relatório final e README explicativo

# Bibliotecas iniciais
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Configuração dos gráficos
sns.set(style="whitegrid")

# Placeholder para carregar os dados (ex: consumo_energia.csv)
# df = pd.read_csv('dados/consumo_energia.csv')

# Exibição inicial do dataset (exemplo)
# print(df.head())

# Aqui faremos: tratamento de dados, conversões de tipos, análises por estado, por fonte, por ano...

# Em breve: análise por tipo de energia, consumo per capita, evolução temporal, etc.

# Exemplo de gráfico (remoção quando for usar dados reais)
# plt.figure(figsize=(10,6))
# sns.lineplot(data=df, x='Ano', y='Consumo_MWh', hue='Fonte')
# plt.title('Consumo de Energia por Tipo de Fonte ao longo dos anos')
# plt.show()
