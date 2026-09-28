# Desafio Prático: Detecção de Fraudes em Cartões de Crédito 💳🛡️

Projeto de análise de dados e Machine Learning desenvolvido para o Bootcamp Bradesco - GenAI, Dados & Cyber ​​, da DIO.
---

## 🚀 Sobre o Projeto
Lidar com fraudes financeiras exige técnicas robustas de tratamento de dados, engenharia de atributos e algoritmos orientados para lidar com classes minoritárias. Este repositório contém todo o fluxo analítico, desde a Análise Exploratória de Dados (EDA) até à modelagem preditiva e avaliação de desempenho.

## 📊 Principais Etapas do Pipeline
1. **Análise Exploratória de Dados (EDA):** Carregamento do dataset real, verificação de tipos e estudo da distribuição das classes (`Normal` vs `Fraude`).
2. **Engenharia de Atributos & Pré-processamento:** Tratamento de variáveis e escalonamento de colunas como o `Amount` para estabilizar os algoritmos.
3. **Modelagem Comparativa:**
   * **Regressão Logística (Baseline):** Modelo linear ajustado com aumento de iterações (`max_iter`) para garantir convergência.
   * **Random Forest:** Abordagem baseada em árvores utilizando pesos balanceados (`class_weight="balanced"`).
   * **XGBoost:** Algoritmo de *gradient boosting* otimizado com ponderação de classes (`scale_pos_weight`) e ajuste fino de limiar (*threshold* otimizado para `0.3`).
4. **Avaliação de Desempenho:** Utilização de relatórios de classificação focando em métricas críticas como *Precision*, *Recall* e *F1-Score* para a classe minoritária.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas
* **Python 3.13**
* **Pandas & NumPy** (Manipulação e computação numérica)
* **Scikit-Learn** (Métricas, modelos lineares e ensembles)
* **XGBoost** (Modelagem preditiva avançada)
* **Matplotlib & Seaborn** (Visualização de dados e gráficos estatísticos)

---

## ⚙️ Como Executar o Projeto
1. Clona este repositório:
   ```bash
   git clone [https://github.com/o-teu-utilizador/o-teu-repositorio.git](https://github.com/o-teu-utilizador/o-teu-repositorio.git)
