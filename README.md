# Credit_Analysis_with_Machine_Learning

# Análise de Crédito com Machine Learning: Modelo Naive Bayes Otimizado
# Resumo do Projeto:

Este projeto demonstra a aplicação do algoritmo Naive Bayes otimizado para análise de crédito, utilizando um conjunto de dados balanceado com a técnica SMOTE. O objetivo é prever se um cliente pagará ou não um empréstimo, com base em suas características socioeconômicas (renda, idade e dívida).


Este código divide os dados em 80% para treino e 20% para teste, utilizando amostragem estratificada para manter a proporção de classes em ambos os conjuntos. A amostragem estratificada garante que a proporção de classes no conjunto de treino seja a mesma que a proporção no conjunto original, evitando vieses no modelo. O random_state garante a reprodutibilidade dos resultados
Pré-processamento de Dados para Treinamento:

As variáveis numéricas são padronizadas para garantir que estejam na mesma escala.
# Treinamento do Modelo Naive Bayes Otimizado:

O modelo Naive Bayes é treinado com os dados de treino e otimizado utilizando a técnica de busca em grade para encontrar os melhores hiperparâmetros.
Realização de Previsões:

O modelo treinado é utilizado para prever a classe de cada cliente no conjunto de teste.
# Avaliação do Modelo

A acurácia, precisão, revocação e F1-score do modelo são calculados para cada classe e no geral.
A curva ROC é gerada para visualizar o desempenho do modelo em diferentes níveis de limiar de probabilidade.
A matriz de confusão é gerada e visualizada com um heatmap para mostrar o número de acertos e erros para cada classe.
# Resultados:

Curva ROC: A curva ROC indica que o modelo tem bom poder discriminatório entre as classes.
Matriz de Confusão: A matriz de confusão mostra que o modelo tem um bom desempenho na classificação de ambas as classes, com um leve viés para a classe "Paga".
