# Projeto 6 — Regressão Polinomial: Previsão de Valor de Aluguel

---

## 📚 Explicação do Curso
Este projeto foi desenvolvido como parte do **MÓDULO 34 - Regressão: Conceitos Avançados** do curso de Cientista de Dados da EBAC. O objetivo central é aplicar e consolidar o conhecimento em modelos de regressão avançada, focando especificamente na **Regressão Polinomial** para previsão de aluguel.

---

## 🎯 Objetivos
O principal objetivo deste projeto é a prática e consolidação da proficiência em modelos de Regressão Polinomial:

* **Seleção de Variável:** Escolher uma variável preditora alternativa à `Valor Condominio` (usada em aula) para prever o `Valor_Aluguel`.
* **Transformação de Dados:** Aplicar a transformação `PolynomialFeatures` com `degree = 2` para criar variáveis não lineares.
* **Modelagem:** Separar os dados em treino e teste e realizar o treinamento do modelo de `LinearRegression` no conjunto transformado.
* **Avaliação de Performance:** Fazer previsões, avaliar os resultados obtidos e plotar o gráfico da regressão ajustada.

---

## 💻 Tecnologias Usadas
* **Linguagem:** Python
* **Manipulação de Dados:** Pandas, NumPy
* **Modelagem:** Scikit-learn (`LinearRegression`, `PolynomialFeatures`, `train_test_split`)
* **Avaliação e Visualização:** Matplotlib, `r2_score`

---

## 📈 Principais Análises Realizadas
O projeto focou nas seguintes etapas de processamento e modelagem:

* **Carregamento e Separação:** A base de dados `ALUGUEL_MOD12.csv` foi carregada, e a variável **`Metragem`** foi selecionada como a variável preditora (X).
* **Feature Engineering:** A `Metragem` foi processada utilizando o **`PolynomialFeatures`** com grau 2.
* **Treinamento:** O modelo foi treinado em um conjunto de dados separado (80% treino, 20% teste).
* **Visualização:** O gráfico de dispersão dos dados reais foi plotado, juntamente com a linha do Ajuste Polinomial.

---

## ✨ Insights Chave (Valor de Negócio e Conclusão)

O exercício demonstrou a proficiência na aplicação de **Regressão Polinomial**, comprovando a capacidade de:

* **Capturar Relações Complexas:** Utilizar a regressão polinomial para modelar relações não lineares entre a `Metragem` e o `Valor_Aluguel`.
* **Avaliação Preditiva:** A performance do modelo (com $R^2$ de **0.5423** no conjunto de teste) fornece uma base sólida para a previsibilidade do valor de aluguel.
* **Escolha de Variável:** A seleção da `Metragem` como variável preditora principal reforça a intuição de que o tamanho do imóvel é um dos fatores mais críticos.
