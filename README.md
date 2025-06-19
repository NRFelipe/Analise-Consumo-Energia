# ⚡ Geração de Energia no Brasil — Análise por Estado, Fonte e Ano

Este projeto analisa a geração de energia elétrica no Brasil utilizando dados públicos da ANEEL (SIGA). O foco está em compreender a distribuição por tipo de fonte (renovável x não renovável), a evolução da entrada de usinas em operação e os estados com maior potência instalada.

---

## 📌 Objetivos

- Identificar os estados com maior geração de energia
- Comparar fontes renováveis e não renováveis
- Analisar o crescimento de usinas por tipo e ao longo do tempo
- Criar um painel interativo com Tableau Public

---

## 📊 Principais Insights

- **UHEs** (Hidrelétricas) lideram em potência instalada
- **UFVs** (Usinas Fotovoltaicas) dominam em número de empreendimentos
- **SP, MG e PA** são os estados com maior geração total
- Crescimento acentuado de usinas **solares** a partir de 2017
- Ponto máximo de novas usinas em **2022**

---

## 🛠️ Ferramentas utilizadas

- Python: `pandas`, `matplotlib`
- Tableau Public: dashboard interativo
- JupyterLite
- Git e GitHub

---

## 📁 Estrutura do Projeto

📦 geracao-energia-brasil
├── dados/
│ └── usinas_tratadas.csv # Dados tratados (pronto para uso no Tableau)
├── notebooks/
│ └── analise-exploratoria.ipynb # Notebook com limpeza e gráficos em matplotlib
├── dashboard/
│ └── link-dashboard.txt # Link para o painel no Tableau Public
├── imagens/
│ └── preview.png # Captura do dashboard
└── README.md

---

## 🚀 Executando o projeto

### 1. Clonar o repositório
```bash
git clone https://github.com/NRFelipe/geracao-energia-brasil.git
