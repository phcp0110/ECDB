# ECDB
Trabalho de análise exploratória e modelação de dados, focado em comparar diferentes algoritmos de classificação (Random Forest, SVM, XGBoost, MLP, entre outros). Inclui pré-processamento, seleção de features, avaliação com cross-validation e testes finais.

📁 Estrutura



🔧 Configuração

    Antes de correr o notebook, certifica-te de que tens o ambiente Python preparado:

      pip install -r requirements.txt

    requirements.txt deve incluir:

      pandas
      numpy
      scikit-learn
      xgboost
      matplotlib
      jupyter




🎯 Funcionalidades principais

    Remoção de features irrelevantes (variância zero)

    Normalização robusta dos dados

    Comparação de modelos (RF, SVM, Logistic Regression, XGBoost, MLP) com validação cruzada (ROC‑AUC)

    Seleção de features por ranking (como top‑50, top‑100) e análise do impacto no desempenho

    Busca visual do número ótimo de features (k)

    Avaliação final no conjunto de teste com métricas detalhadas (AUC, acurácia, matriz de confusão)
