# Прогнозирование оттока клиентов в сети отелей «Как в гостях»

<b>Цель работы: </b>

- Построение модели, предсказывающей отказ от брони
  
Нужно разработать систему, которая предсказывает отказ от брони. Если модель покажет, что бронь будет отменена, то клиенту предлагается внести депозит. Размер депозита — 80% от стоимости номера за одни сутки и затрат на разовую уборку. Деньги будут списаны со счёта клиента, если он всё же отменит бронь.  
  
<b> Согласно документации: </b>
- `id` — номер записи;
- `adults` — количество взрослых постояльцев;
- `arrival_date_year` — год заезда;
- `arrival_date_month` — месяц заезда;
- `arrival_date_week_number` — неделя заезда;
- `arrival_date_day_of_month` — день заезда;
- `babies` — количество младенцев;
- `booking_changes` — количество изменений параметров заказа;
- `children` — количество детей от 3 до 14 лет;
- `country` — гражданство постояльца;
- `customer_type` — тип заказчика:
- `Contract` — договор с юридическим лицом;
- `Group` — групповой заезд;
- `Transient` — не связано с договором или групповым заездом;
- `Transient-party` — не связано с договором или групповым заездом, но связано с бронированием типа Transient.
- `days_in_waiting_list` — сколько дней заказ ожидал подтверждения;
- `distribution_channel` — канал дистрибуции заказа;
- `is_canceled` — отмена заказа;
- `is_repeated_guest` — признак того, что гость бронирует номер второй раз;
- `lead_time` — количество дней между датой бронирования и датой прибытия;
- `meal` — опции заказа:  
    - SC — нет дополнительных опций;  
    - BB — включён завтрак;  
    - HB — включён завтрак и обед;  
    - FB — включён завтрак, обед и ужин.  
- `previous_bookings_not_canceled` — количество подтверждённых заказов у клиента;
- `previous_cancellations` — количество отменённых заказов у клиента;
- `required_car_parking_spaces` — необходимость места для автомобиля;
- `reserved_room_type` — тип забронированной комнаты:
    - категория A: за ночь — 1 000, разовое обслуживание — 400;
    - категория B: за ночь — 800, разовое обслуживание — 350;
    - категория C: за ночь — 600, разовое обслуживание — 350;
    - категория D: за ночь — 550, разовое обслуживание — 150;
    - категория E: за ночь — 500, разовое обслуживание — 150;
    - категория F: за ночь — 450, разовое обслуживание — 150;
    - категория G: за ночь — 350, разовое обслуживание — 150. 
- `stays_in_weekend_nights` — количество ночей в выходные дни;
- `stays_in_week_nights` — количество ночей в будние дни;
- `total_nights` — общее количество ночей;
- `total_of_special_requests` — количество специальных отметок.

<b> Используемые библиотеки: </b>
- pandas
- math
- matplotlib.pyplot
- sklearn.tree.DecisionTreeClassifier
- sklearn.ensemble.RandomForestClassifier
- sklearn.linear_model.LogisticRegression
- sklearn.model_selection.train_test_split
- sklearn.preprocessing.StandardScaler 
- sklearn.metrics.f1_score, roc_auc_score, roc_curve, recall_score
- sklearn.dummy.DummyClassifier
- sklearn.utils.shuffle
- sklearn.model_selection.cross_val_score, GridSearchCV
- sklearn.preprocessing.OrdinalEncoder
- warnings
- pandas.core.common.SettingWithCopyWarning


```python

```
