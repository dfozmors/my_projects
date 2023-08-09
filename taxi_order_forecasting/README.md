# Прогнозирование заказов такси
  
<b> Цель работы:</b> 
- Построить модель, которая будет предсказывать количество заказов такси на следующий час

<b>Задачи: </b>
- Значение метрики RMSE на тестовой выборке должно быть не больше 48.

<b> Согласно документации: </b>  
- `datetime` — Время 
- `num_orders` — Количество заказов
 

<b> Используемые библиотеки: </b>
- pandas
- numpy
- matplotlib.pyplot
- statsmodels.tsa.seasonal.seasonal_decompose 
- sklearn.model_selection.TimeSeriesSplit
- sklearn.model_selection.train_test_split
- sklearn.tree.DecisionTreeRegressor
- sklearn.ensemble.RandomForestRegressor
- sklearn.linear_model.LinearRegression
- catboost
- sklearn.model_selection.GridSearchCV
- sklearn.metrics.mean_squared_error
