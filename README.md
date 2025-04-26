# 📊 Projeto de Clusterização de Clientes

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Colab](https://img.shields.io/badge/Google%20Colab-Executed-yellow?logo=googlecolab)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)

---

## 📋 Sobre o Projeto

Este notebook realiza uma análise de comportamento de compra de clientes com o objetivo de segmentá-los em grupos (clusters) de características semelhantes.

**Principais etapas realizadas:**
- Carregamento e tratamento da base de dados.
- Remoção de pedidos cancelados ou não pagos.
- Criação de identificador único para cada cliente.
- Cálculo do gasto total, quantidade comprada, valor de frete e frequência (com base em pedidos únicos).
- Normalização dos dados com `StandardScaler`.
- Definição do número ideal de clusters usando o método do cotovelo.
- Aplicação do algoritmo `KMeans` para agrupamento dos clientes.
- Análise dos clusters gerados (gasto médio, frequência média).
- Geração de visualizações gráficas e exportação dos resultados em Excel.

**Resultado:**  
Segmentação dos clientes em 4 clusters distintos, possibilitando ações de marketing direcionadas para melhorar a retenção, fidelização e maximizar a experiência de compra.

---

## 🔍 Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (StandardScaler, KMeans)
- Google Colab

---

## 📂 Estrutura do Projeto

/analise-cluster-clientes/
│
├── codigo_analise.ipynb         # Código da análise e clusterização
├── relatorio_final.pdf          # Relatório de insights em PDF
├── grafico_comparativo.png      # Gráficos comparativos dos clusters
├── README.md                    # Descrição do projeto
└── data/
├── base_original.xlsx        # Base original (anonimizada)
└── clientes_com_clusters.xlsx # Base tratada e clusterizada

---

## ⚙️ Como Reproduzir a Análise

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/analise-cluster-clientes.git

   	2.	Abra o arquivo codigo_analise.ipynb no Google Colab ou Jupyter Notebook.
	3.	Faça o upload da base de dados anonimizado_tabela_pedidos_site_consolidada.xlsx.
	4.	Execute o notebook para reproduzir toda a análise, clusterização e geração de relatórios.
	5.	Visualize os insights nos gráficos e no relatório final.

   🎯 Principais Resultados
	•	Identificação de quatro grupos de clientes com comportamentos distintos:
	•	Novos/Ocasional: Compra única e baixo ticket médio
	•	VIP Unitário: Alto gasto, baixa frequência
	•	Fidelizados: Compradores regulares e frequentes
	•	Empresarial/Bulk: Clientes com volume de compra intermediário-alto
	•	Definição de estratégias de marketing personalizadas para cada perfil de cliente.

   ✨ Observação

As bases de dados utilizadas foram anonimizadas para fins acadêmicos e respeitam princípios de privacidade.

⸻
📬 Contato

Caso queira discutir o projeto, trocar ideias ou sugerir melhorias, estou à disposição!

⸻
