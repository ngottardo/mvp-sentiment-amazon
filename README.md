# MVP: Machine Learning & Analytics - Amazon Fine Food Reviews

**Nome:** Natália Gottardo Costa Oliveira  
**Data:** 27/08/2025  
**Dataset:** [Amazon Fine Food Reviews](https://drive.google.com/file/d/1KGRJsHXpbcSuTLeQaHC52vn9yGnaH5yr/view?usp=sharing) (Drive)

---

## Descrição

Este notebook realiza uma análise de sentimentos (positivo/negativo) a partir das reviews de produtos alimentícios da Amazon.  
O pipeline inclui:  
- Limpeza e pré-processamento do texto (`text_clean`)  
- Engenharia de atributos (número de palavras por review)  
- Modelos de baseline (Naive Bayes, Logistic Regression)  
- Hiperparâmetros otimizados via `RandomizedSearchCV`  
- Avaliação final com métricas de F1, accuracy e matriz de confusão

