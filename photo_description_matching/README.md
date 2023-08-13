# Поиск изображений по запросу (Статус проекта - Завершен)

<b> Цель работы:</b> 
- Обучить модель, которая получит векторное представление изображения, векторное представление текста, а на выходе выдаст число - покажет, насколько текст и картинка подходят друг другу.

<b> Согласно документации: </b>  

- `image` — Имя файла изображения
- `query_id` — Идентификатор описания 
- `query_text` — Описание фотографии  
- `share_pos` — Доля людей, подтвердивших, что описание соответствует изображению. 
- `count_pos` — Количество человек, подтвердивших, что описание соответствует изображению.
- `count_neg` — Количество человек, подтвердивших, что описание не соответствует изображению.  
- `1` — Оценка первого эксперта 
- `1.1` — Оценка 2 эксперта
- `1.2` — Оценка 3 эксперта



<b> Используемые библиотеки: </b>
- pandas
- numpy
- matplotlib.pyplot
- nltk
- re
- PIL.Image
- pathlib
- tensorflow.keras.layers
- keras_nlp   
- sklearn
- tensorflow.keras.preprocessing.image.ImageDataGenerator
- tensorflow.keras.applications.resnet.ResNet50
- tensorflow.keras.layers.GlobalAveragePooling2D, Dense
- tensorflow.keras.models.Sequential
- tensorflow.keras.optimizers.Adam
- os