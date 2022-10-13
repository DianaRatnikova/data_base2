# data_base2
Learn Python DB2 (Week5)
Выполнен 2ой трек по безем данных LearnPython
 
1. Создание таблицы и загрузка в нее данные из csv-файла
2. Осуществление запросов с  использованием сортировки и фильтрации


## Сборка репозитория и локальный запуск
Выполните в консоли:
```
git clone https://github.com/DianaRatnikova/data_base2
pip install -r requirments.txt
```
 
### Создание базы данных
Создайте БД на ElephantSQL, откройте её в ValentinaStudio
```
https://customer.elephantsql.com/instance
https://www.valentina-db.com/
```

### Создание файла csv с фейковыми данными
Из корня проекта запустите конструктор базы данных:
```
python create_data.py
```


### Создание таблицы salaries базы данных
Из корня проекта запустите конструктор базы данных:
```
python models.py
```

### Заполнение таблицы salaries фейковыми данными
Из корня проекта запустите загрузчик данных:
```
python loader.py
```

### Выполнение запросов
Для выполнения запросов запустите из корня проекта:
```
python queries.py
```

