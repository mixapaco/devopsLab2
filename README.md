
# 2
Команди для створення віртуального середовища
```
python3 -m pip install pipenv;
python3 -m pipenv --python 3.7;
	
```
---

# 3
Команди для завантаження бібліотек
```
python3 -m pipenv install requests;
python3 -m pipenv install ntplib;
```
---

# 5
### Перевірка роботи програми
```
python3 -m pipenv run python app.py
========================================
Результат без параметрів: 
No URL passed to function
========================================
Результат з правильною URL: 
Time is:  08:28:25 PM
Date is:  10-04-2020
Доброї ночі

```
---

# 6
Команда для завнтаження бібліотеки для тестів
```
python3 -m pipenv install pytest;
```

# 10
Перенаправлення у файл
```
python3 -m pipenv run pytest tests/tests.py > results.txt; python3 -m pipenv run python app.py >> results.txt
```
