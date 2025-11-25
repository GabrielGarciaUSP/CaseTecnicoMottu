# 🛵 Mottu Case Study: Turnover Analysis & Investment Thesis

Este repositório contém a resolução do Case Técnico e Estratégico proposto pela Mottu. O projeto foi dividido em duas frentes: uma análise de dados quantitativa (Python) sobre retenção de talentos e uma tese de investimento qualitativa (VC perspective).

---

## 📋 Estrutura do Projeto

O projeto está organizado em duas questões principais:

### 1. Análise de Turnover Operacional ("Mecânicos Faixa Preta")
**Objetivo:** Avaliar a eficácia do programa de certificação técnica e investigar as causas da estabilidade do turnover em 30%.

* **Ferramentas:** Python, Pandas, Matplotlib.
* **Principais Insights Descobertos:**
    * ✅ **Eficácia Comprovada:** O programa "Faixa Preta" blinda a operação. O turnover entre colaboradores certificados é residual (< 0.5%), contra uma média de ~3% nos não-certificados.
    * ⚠️ **Risco de Safra (Tenure):** Identificou-se que o maior volume de saídas (38%) não ocorre na experiência, mas na faixa de **6 a 12 meses** de casa.
    * 🔍 **Causa Raiz:** 59% das saídas nesse período crítico são **pedidos de demissão** (voluntários).
    * **Conclusão:** A empresa perde talentos produtivos e já treinados *antes* que eles se tornem elegíveis à certificação.

### 2. Tese de Investimento (Bear Case)
**Objetivo:** Construir uma tese contrária ao investimento na Mottu sob a ótica de um fundo de Venture Capital.

* **Foco:** Análise de Riscos Financeiros e Operacionais.
* **Pontos de Atenção Levantados:**
    * **Capex Intensivo vs. Custo da Dívida:** O desafio de dobrar a frota em um cenário de Selic elevada, pressionando o fluxo de caixa livre.
    * **Risco de Crédito (Modelo Conquiste):** A exposição à inadimplência de público não-bancarizado (subprime) e o impacto direto no *Unit Economics* em caso de oscilação da demanda da *Gig Economy*.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3.x
* **Análise de Dados:** Pandas, NumPy
* **Visualização:** Matplotlib
* **Ambiente:** Jupyter Notebook

---

## 🚀 Como Executar o Código

1.  Clone este repositório:
    ```bash
    git clone https://github.com/GabrielGarciaUSP/CaseTecnicoMottu.git
    ```
2.  Instale as dependências:
    ```bash
    pip install pandas matplotlib openpyxl
    ```
3.  Abra o arquivo `analise_turnover.ipynb` no Jupyter Notebook ou VS Code.

> **Nota de Compliance:** O arquivo original de dados (`.xlsx`) **não** foi incluído neste repositório para preservar a confidencialidade das informações da empresa. O código serve como demonstração da lógica e estruturação analítica aplicada.

---

## 📊 Visualizações Chave

![Gráfico Turnover Mensal](img/img1.png)
![Gráfico Tenure](img/img2.png)
![Gráfico Saída Momento Crítico](img/img3.png)

O notebook gera gráficos detalhados sobre:
1.  Evolução temporal do Turnover (Faixa Preta vs. Normais).
2.  Análise de Safra (Volume de saídas por tempo de casa).
3.  Ranking de motivos de desligamento.

---

## 👨‍💻 Autor

Desenvolvido por **Gabriel Garcia Ferreira**

Estudante de **Engenharia de Computação** com foco em Análise de Dados e Resolução de Problemas de Negócio.

* [LinkedIn](linkedin.com/in/gabriel-garcia-80b393307/)
* [Email](gabrielgarcia.ata@gmail.com)

---
*Projeto desenvolvido como parte de processo seletivo, demonstrando capacidade de entrega rápida (24h) e profundidade analítica.*