# Проверка возможности оценки риска ДТП
  
<b> Цель работы:</b> 
- Определение основных факторов ДТП и построение модели определяющей виновен человек в аварии или нет

<b>Задачи: </b>
- Изучить данные
- Посмотреть в какие месяцы происходило больше всего аварий
- Построение модели
- Определение ключевых факторов

## <b> Согласно документации: </b>  
<b> Таблица collisions: </b>
-`CASE_ID` - Идентификационный номер в базе данных 
-`COLLISION_DATE` - Дата происшествия 
-`COLLISION_TIME` - Время происшествия
-`INTERSECTION` - Является ли место происшествие перекрёстком 
-`WEATHER_1` - Погода 
-`COLLISION_DAMAGE` - Серьёзность происшествия 
-`PRIMARY_COLL_FACTOR` - Основной фактор аварии 
-`ROAD_SURFACE` - Состояние дороги
-`LIGHTING` - Освещение 
-`COUNTY_CITY_LOCATION` - Номер географических районов, где произошло ДТП 
-`COUNTY_LOCATION` - Названия географических районов, где произошло ДТП 
-`DIRECTION` - Направление движения 
-`DISTANCE` - Расстояние от главной дороги (метры)
-`LOCATION_TYPE` - Количество участников 
-`PARTY_COUNT` - Номер географических районов, где произошло ДТП 
-`PCF_VIOLATION_CATEGORY` - Категория нарушения 
-`TYPE_OF_COLLISION` - Тип аварии 
-`MOTOR_VEHICLE_INVOLVED_WITH` - Дополнительные участники ДТП 
-`ROAD_CONDITION_1` - Дорожное состояние
-`CONTROL_CONDITION_1` - Устройство управления 

<b> Таблица Parties: </b>
-`CASE_ID` - Идентификационный номер в базе данных 
-`PARTY_NUMBER` - Номер участника происшествия 
-`PARTY_TYPE` - Тип участника происшествия
-`AT_FAULT` - Виновность участника
-`INSURANCE_PREMIUM` - Сумма страховки (тыс. $) 
-`PARTY_DRUG_PHYSICAL` - Состояние участника: физическое или с учётом принятых лекарств 
-`PARTY_SOBRIETY` - Трезвость участника 
-`CELLPHONE_IN_USE` - Наличие телефона в автомобиле (возможности разговаривать по громкой связи) 

<b> Таблица Vehicles: </b>
-`CASE_ID` - Идентификационный номер в базе данных 
-`ID` - Индекс текущей таблицы
-`VEHICLE_TYPE` - Тип кузова
-`VEHICLE_TRANSMISSION` - Тип КПП
-`VEHICLE_AGE` - Возраст автомобиля (в годах) 



<b> Используемые библиотеки: </b>
- pandas
- numpy
- math
- matplotlib.pyplot
- sklearn.model_selection.train_test_split
- sklearn.preprocessing.StandardScaler 
- sklearn.preprocessing.OrdinalEncoder
- sklearn.preprocessing. OneHotEncoder
- sklearn.linear_model.LogisticRegression
- sklearn.tree.DecisionTreeClassifier
- sklearn.ensemble.RandomForestClassifier
- sklearn.metrics.f1_score, confusion_matrix, precision_recall_curve
- sklearn.feature_extraction.text. TfidfVectorizer
- catboost
- xgboost.XGBRegressor
- shap
- sklearn.model_selection.cross_val_score, GridSearchCV
