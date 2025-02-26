📌 Classificação de Tumores de Mama com Machine Learning
Este repositório contém um código para a classificação de tumores de mama, utilizando Aprendizado de Máquina com a biblioteca scikit-learn. O modelo foi treinado com o conjunto de dados breast_cancer disponível no sklearn.datasets, aplicando Support Vector Machine (SVM) e técnicas de pré-processamento para otimizar a precisão da classificação.

📊 Descrição do Projeto
O objetivo deste projeto é prever se um tumor de mama é benigno ou maligno com base em características extraídas de exames. Para isso, foram aplicados os seguintes passos:

✔ Carregamento dos dados: load_breast_cancer do sklearn.datasets.
✔ Pré-processamento: Normalização dos dados com StandardScaler.
✔ Divisão do conjunto de dados: Separação em treino e teste (train_test_split).
✔ Treinamento do modelo: Algoritmo SVM (Support Vector Machine).
✔ Otimização dos hiperparâmetros: GridSearchCV.
✔ Avaliação do modelo: Relatórios de classificação e matriz de confusão.

🛠 Tecnologias Utilizadas
Python 🐍
scikit-learn (Machine Learning)
NumPy (Manipulação de arrays)
Pandas (Análise e manipulação de dados)
Matplotlib e Seaborn (Visualização de dados)
