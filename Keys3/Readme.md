# Приложение для создания ToDo-листов.

Перед установкой убедиться, что на компьютере установлены python 3 и pip

## Инструкция для установки на Windows/Linux через CLI.

1. Перейти в папку Kurs1\Keys3

2. Выполнить команды:

2. 1 Для Windows
```
python -m venv .venv
source .venv\Scripts\activate
pip install -r requirements.txt
```

2. 2 Для Linux 
```
python -m venv .venv
source ./venv/bin/activate
pip install -r requirements.txt
```
## Запуск приложения
1) Для запуска приложения в CLI выполнить команду:
```
python app.py
```
2) Перейти на главную страницу приложения по адресу http://127.0.0.1:5000/

----
По умолчанию уже введены тестовые записи, их можно удалить через браузер или удалив файл базы данных __todo.db__
Для создания новой базы данных выполните в CLI команду: 
```
python create_db.py
```
