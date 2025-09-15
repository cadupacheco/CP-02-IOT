# 🧠 Exercícios de Redes Neurais com Keras e Scikit-learn

Este repositório contém a implementação de exercícios práticos utilizando **redes neurais em Keras** e modelos clássicos do **Scikit-learn**.  
O objetivo é comparar desempenho entre abordagens de **Deep Learning** e **Machine Learning tradicional** em diferentes tarefas.

---

## 📂 Estrutura do Projeto

- `Exercicio1_Wine_Classification.ipynb`  
  Classificação multiclasse no **Wine Dataset (UCI)**.  
  - Rede Neural (Keras): 2 camadas ocultas de 32 neurônios (ReLU) + saída Softmax.  
  - Comparação com **RandomForestClassifier** e **LogisticRegression**.  
  - Métrica utilizada: **Acurácia**.

- `Exercicio2_CaliforniaHousing_Regression.ipynb`  
  Regressão no **California Housing Dataset (Scikit-learn)**.  
  - Rede Neural (Keras): 3 camadas ocultas (64, 32, 16 neurônios ReLU) + saída Linear.  
  - Comparação com **LinearRegression** e **RandomForestRegressor**.  
  - Métricas utilizadas: **RMSE** e **MAE**.

---

## 🚀 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Crie e ative um ambiente virtual (opcional, mas recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
   ```

3. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```

4. Execute os notebooks:
   ```bash
   jupyter notebook
   ```

---

## 📊 Resultados Esperados

- **Wine Dataset**:  
  - RandomForest e LogisticRegression costumam ter ótimo desempenho, próximo ou até superior à rede neural.  
  - Rede neural pode alcançar **acurácia acima de 95%** após poucas épocas.  

- **California Housing Dataset**:  
  - LinearRegression serve como baseline simples.  
  - RandomForest geralmente apresenta menor erro (RMSE/MAE).  
  - Rede neural pode atingir resultados competitivos após ajuste de hiperparâmetros.  

---

## 👨‍💻 Desenvolvedores

- Carlos Eduardo Rodrigues Coelho Pacheco — RM557323  
- Pedro Augusto Costa Ladeira — RM558514  

