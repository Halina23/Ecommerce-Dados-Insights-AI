# 📊 Análise de Faturamento de E-commerce com Python

## 📌 Objetivo do Projeto

O objetivo deste projeto foi realizar uma **análise exploratória de dados de vendas de um e-commerce** utilizando Python no Google Colab e, a partir dos resultados obtidos, **gerar insights de negócio com apoio de Inteligência Artificial**.

Os dados utilizados foram extraídos de um **banco de dados PostgreSQL previamente modelado para um cenário de e-commerce**, exportados para **Excel** e posteriormente carregados no ambiente de análise.

Este projeto demonstra um fluxo comum em análise de dados:

Banco de Dados → Extração → Análise em Python → Interpretação de Insights

---

# 🗂 Fonte dos Dados

Os dados utilizados foram gerados a partir de um **banco de dados de e-commerce desenvolvido para fins de análise**, contendo informações sobre vendas.

Para facilitar a análise no notebook, os dados foram exportados para **Excel** e carregados no **Google Colab** utilizando a biblioteca **Pandas**.

---

# ⚙️ Tecnologias Utilizadas

* **Python**
* **Pandas**
* **Matplotlib**
* **Google Colab**
* **Excel**
* **PostgreSQL (origem dos dados)**
* **IA generativa para interpretação dos resultados**

---

# 📥 Carregamento dos Dados

Os dados foram carregados no notebook a partir de um arquivo Excel. Após o carregamento, foram realizados procedimentos básicos de **limpeza de dados**, como remoção de linhas vazias.

# 📊 Cálculo de Métricas

Foi calculado o crescimento percentual do faturamento entre os meses, isso permitiu identificar variações mensais no desempenho de vendas.

---

# 📈 Resultado da Análise

| Mês      | Faturamento | Crescimento |
| -------- | ----------- | ----------- |
| Ago/2025 | 395.193     | -           |
| Set/2025 | 651.219     | 64.78%      |
| Out/2025 | 391.515     | -39.87%     |
| Nov/2025 | 574.099     | 46.63%      |
| Dez/2025 | 566.565     | -1.31%      |
| Jan/2026 | 639.087     | 12.80%      |
| Fev/2026 | 414.735     | -35.10%     |
| Mar/2026 | 59.403      | -85.67%     |

---

# 🔍 Insights Gerados

A interpretação dos resultados foi realizada com auxílio de **IA generativa**, utilizando os dados produzidos na análise.

Principais observações:

* **Setembro apresentou forte crescimento (+64%)** em relação a agosto, indicando um período de alta nas vendas.
* **Outubro apresentou queda significativa (-39%)**, possivelmente após um pico de vendas no mês anterior.
* **Novembro demonstrou recuperação expressiva (+46%)**, indicando retomada da demanda.
* **Dezembro apresentou estabilidade nas vendas**, com pequena variação negativa.
* **Março apresentou queda extrema (-85%)**, o que pode indicar **dados de mês incompleto** ou mudança no comportamento de vendas.

---

# 📊 Visualização de Dados

Foi gerado um gráfico de faturamento mensal para facilitar a identificação de tendências.

---

# 💡 Conclusão

Este projeto demonstra como é possível combinar:

* **Análise de dados com Python**
* **Estruturação de dados provenientes de banco relacional**
* **Interpretação assistida por Inteligência Artificial**

para gerar **insights de negócio a partir de dados de vendas**.

A abordagem reforça a importância da **exploração e preparação de dados antes da etapa de interpretação**, além de mostrar como ferramentas de IA podem auxiliar na análise estratégica.

---

# 📁 Estrutura do Projeto

```
📂 ecommerce-insights
 ┣ 📄 Ecommerce Novo.xlsx
 ┣ 📄 analise_vendas.ipynb
 ┗ 📄 README.md
```

---

# 👩‍💻 Autora

Projeto desenvolvido por **Halina** como parte do desenvolvimento de portfólio em **Data Analytics**.
