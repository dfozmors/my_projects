# Рекоммендация тарифовов   (Статус проекта - Завершен)

<b> Цель: </b>  
- На основе данных о поведении клиентов,  нужно построить модель для задачи классификации, которая выберет подходящий тариф. Модель должна быть с максимальным значением accuracy

<b> Согласно документации: </b>  
- `сalls` — количество звонков,
- `minutes` — суммарная длительность звонков в минутах,
- `messages` — количество sms-сообщений,
- `mb_used` — израсходованный интернет-трафик в Мб,
- `is_ultra` — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).

<b> Используемые библиотеки: </b>
- pandas
- sklearn.tree.DecisionTreeClassifier
- sklearn.ensemble.RandomForestClassifier
- sklearn.linear_model.LogisticRegression
- sklearn.model_selection.train_test_split
- sklearn.metrics.mean_squared_error
- sklearn.metrics.accuracy_score 
- sklearn.dummy.DummyClassifier
