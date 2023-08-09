**Цель исследования** 
Построить нейросеть, которая будет определять температуру на поверхности обнаруженных звезд


<b>Согласно документации:</b>
- `temperature` — температура звезды;
- `Luminosity` — светимость звезды относительно Солнца.;
- `Radius` — радиус звезды относительно радиуса Солнца.;
- `Absolute magnitude` — физическая величина, характеризующая блеск звезды.;
- `Star type` — тип звезды;
- `Star color` - цвет звезды
- `Day` - День недели, в который был прослушан трек;


<b>libraries used:</b>

- random
- numpy as np
- pandas as pd
- seaborn as sns
- matplotlib.pyplot as plt
- math import ceil
- torch
- torch.nn 
- sklearn.preprocessing.OneHotEncoder
- sklearn.metrics.mean_squared_error
- sklearn.model_selection.train_test_split
- sklearn.preprocessing.StandardScaler, OneHotEncoder