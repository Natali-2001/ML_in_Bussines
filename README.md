# Итоговый проект курса "Машинное обучение в бизнесе"

Данные: https://www.kaggle.com/teejmahal20/airline-passenger-satisfaction

### Задача: 
Предсказать удовлетворенность пассажира сервисом авиакомпании по данным опроса. Бинарная классификация.

### Запуск:

Запусть Flask-приложение: app/run_server.py
Использовать функцию get_prediction из app/get_predictions.py для получения предсказаных значений


Функция get_prediction: Принимает на вход pandas-датафрейм. Возможно подать на вход функции как одну строку, так и целый датафрейм. Возвращает json-объект со списком предсказанных значений. Значений имеют тип 'str': 'satisfied'/'neutral or dissatisfied'.

Директории App:

'/datasets/' - содержит датасеты в формате .csv

'/models/' - содержит предобученную модель в формате .dill

'/notebooks/' - содержит блокноты Jupyter Noutbook с этапами создания модели классификации
