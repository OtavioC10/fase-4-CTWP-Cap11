# Fase-4-CTWP-Cap11

# 🌾 Classificação de Grãos de Trigo com Aprendizado de Máquina

Este projeto tem como objetivo desenvolver um modelo de machine learning para classificar variedades de trigo com base em características físicas, utilizando a metodologia **CRISP-DM** e o conjunto de dados **Seeds Dataset** da UCI Machine Learning Repository.

---

## 📚 Metodologia: CRISP-DM

### 1. Entendimento do Negócio
Em cooperativas agrícolas, a classificação de grãos ainda é feita manualmente por especialistas, o que pode ser demorado e sujeito a erros. Este projeto busca automatizar essa tarefa com técnicas de aprendizado de máquina.

### 2. Entendimento dos Dados
- **Dataset:** Seeds Dataset (UCI)
- **Total de Amostras:** 210
- **Classes:** 3 variedades de trigo (Kama, Rosa, Canadian)
- **Atributos:**
  - Área
  - Perímetro
  - Compacidade
  - Comprimento do Núcleo
  - Largura do Núcleo
  - Coeficiente de Assimetria
  - Comprimento do Sulco do Núcleo
  - Classe (1, 2 ou 3)

### 3. Preparação dos Dados
- Carregamento e exploração inicial do dataset
- Visualização de distribuições com histogramas e boxplots
- Verificação de outliers e correlações
- Padronização dos dados com `StandardScaler`

### 4. Modelagem
Modelos de classificação testados:
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest
- Naive Bayes
- Regressão Logística

Métricas avaliadas:
- Acurácia
- Precisão
- Recall
- F1-Score
- Matriz de Confusão

### 5. Otimização
Foi realizada otimização de hiperparâmetros usando `GridSearchCV`, com foco em melhorar o desempenho do modelo KNN.

### 6. Avaliação e Insights
- Comparação entre modelos com base em desempenho
- Discussão sobre robustez, sensibilidade a outliers e adequação ao ambiente agrícola
- Modelos como Random Forest e SVM mostraram ótimo desempenho e estabilidade

---

## 🛠️ Tecnologias Utilizadas

- Python
- Google Colab / Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn (modelos, métricas e pré-processamento)

---

## 👨‍👩‍👦‍👦 Integrantes do Grupo

- Matheus Parra – RM: 561907  
- Otavio Custodio de Oliveira – RM: 565606  
- Tiago Alves Cordeiro – RM: 561791  
- Thiago Henrique Pereira de Almeida Santos – RM: 563327  
- Leandro Arthur Marinho Ferreira – RM: 565240

---

## 📎 Referência

- [Seeds Dataset – UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/236/seeds)

---

## 📁 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/usuario/repositorio.git
