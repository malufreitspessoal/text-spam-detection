# Classificação de Spam com Naive Bayes

Este projeto implementa um modelo de classificação de mensagens de texto (SMS) como _spam_ ou _ham_ (não spam). O modelo utiliza **Naive Bayes** e técnicas de **Processamento de Linguagem Natural (NLP)**, incluindo vetorização com `TfidfVectorizer`.

## 📌 Funcionalidades
- Carregamento e pré-processamento do dataset `spam.csv`
- Remoção de caracteres especiais e normalização do texto
- Codificação de rótulos (_ham_ ou _spam_)
- Vetorização do texto usando **TF-IDF**
- Treinamento de um modelo **Naive Bayes**
- Avaliação do desempenho do modelo com métricas como **acurácia, precisão, recall e F1-score**

## 🛠 Tecnologias utilizadas
- `pandas`
- `sklearn` (Scikit-learn)
- `re` (expressões regulares)
- `TfidfVectorizer`
- `MultinomialNB`

## 📊 Resultados

O desempenho do modelo Naive Bayes na classificação de spam apresentou as seguintes métricas:

- **Acurácia:** ~97%  
- **Precisão:** ~100%  
- **Recall:** ~81%  
- **F1-score:** ~89%  

Esses resultados indicam que o modelo tem uma alta precisão na identificação de mensagens de spam, embora o recall possa ser melhorado para captar mais mensagens classificadas corretamente como spam.

