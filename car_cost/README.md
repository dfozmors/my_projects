# Определение стоимости автомобилей (Статус проекта - Завершен)
  
<b> Цель работы:</b> 
- Построить модель, которая по техническим характеристикам, комплектации и изначальной цене автомобиля определит стоимость при перепродаже.

<b> Согласно документации: </b>  
- `Price` — цена (евро)  
- `DateCrawled` — дата скачивания анкеты из базы  
- `VehicleType` — тип автомобильного кузова  
- `RegistrationYear` — год регистрации автомобиля  
- `Gearbox` — тип коробки передач    
- `Power` — мощность (л. с.)  
- `Model` — модель автомобиля  
- `Kilometer` — пробег (км)  
- `RegistrationMonth` — месяц регистрации автомобиля  
- `FuelType` — тип топлива  
- `Brand` — марка автомобиля  
- `Repaired` — была машина в ремонте или нет  
- `DateCreated` — дата создания анкеты  
- `NumberOfPictures` — количество фотографий автомобиля  
- `PostalCode` — почтовый индекс владельца анкеты (пользователя)  
- `LastSeen` — дата последней активности пользователя  

<b> Используемые библиотеки: </b>
- pandas
- numpy
- math
- sklearn.model_selection.train_test_split
- sklearn.preprocessing.StandardScaler 
- sklearn.preprocessing.OrdinalEncoder
- sklearn.tree.DecisionTreeClassifier
- sklearn.ensemble.RandomForestClassifier
- sklearn.linear_model.LinearRegression
- lightgbm.LGBMRegressor
- catboost.cv
- catboost.CatBoostRegressor
- xgboost.XGBRegressor
- sklearn.model_selection.cross_val_score, GridSearchCV
- sklearn.metrics.mean_squared_error
