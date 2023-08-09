# Классификация комментариев
  
<b> Цель работы:</b> 
- Обучить модель классифицировать комментарии на позитивные и негативные

<b>Задачи: </b>
- Построить модель со значением метрики качества F1 не меньше 0.75.

<b> Согласно документации: </b>  
- `text` — Текст комментария  
- `toxic` — Является ли комментарий негативным  


<b> Используемые библиотеки: </b>
- pandas
- numpy
- nltk
- sklearn.model_selection.train_test_split
- sklearn.tree.DecisionTreeClassifier
- sklearn.ensemble.RandomForestClassifier
- sklearn.linear_model.LogisticRegression
- catboost
- sklearn.model_selection.cross_val_score, GridSearchCV
- sklearn.metrics.f1_score
- nltk.corpus.stopwords.nltk_stopwords
- tqdm.notebook
- sklearn.feature_extraction.text.TfidfVectorizer