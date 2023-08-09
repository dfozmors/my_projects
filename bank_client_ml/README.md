# Отток клиентов  
  
Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. 

<b>Цель проекта: </b>

- Построить модель, прогназирующую уйдет клиент или нет

<b>Задачи: </b>

- F1 - метрика должна быть более 0.59


Источник данных: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)  

<b> Согласно документации: </b>  
- `RowNumber` — индекс строки в данных
- `CustomerId` — уникальный идентификатор клиента
- `Surname` — фамилия
- `CreditScore` — кредитный рейтинг
- `Geography` — страна проживания
- `Gender` — пол
- `Age` — возраст
- `Tenure` — сколько лет человек является клиентом банка
- `Balance` — баланс на счёте
- `NumOfProducts` — количество продуктов банка, используемых клиентом
- `HasCrCard` — наличие кредитной карты
- `IsActiveMember` — активность клиента
- `EstimatedSalary` — предполагаемая зарплата
- `Exited` — факт ухода клиента

<b> Используемые библиотеки: </b>
- pandas
- numpy
- matplotlib.pyplot
- sklearn.tree.DecisionTreeClassifier
- sklearn.ensemble.RandomForestClassifier
- sklearn.linear_model.LogisticRegression
- sklearn.model_selection.train_test_split
- sklearn.preprocessing.StandardScaler 
- sklearn.metrics.f1_score, roc_auc_score, roc_curve
- sklearn.dummy.DummyClassifier
- sklearn.utils.shuffle
