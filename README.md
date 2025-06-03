# api_yamdb
## Описание  <a id="Content"></a> 
Сервис собирает отзывы пользователей на произведения: "Фильмы", "Музыка", "Книги".
___
##  Установка
### Как запустить проект:

1.Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:ShunyaBo/api_user_feedback.git
```

```
cd api_user_feedback
```

2.Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
# для OS Lunix и MacOS
source venv/bin/activate

# для OS Windows
source venv/Scripts/activate
```

3.Обновить pip:

```
python3 -m pip install --upgrade pip
```

4.Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

5.Выполнить миграции на уровне проекта:

```
python3 manage.py makemigrations
python3 manage.py migrate
```
6.Запустить проект, находясь в директории, где расположен файл manage.py
```
python3 manage.py runserver
```
___
## Авторы
[Антон Шапиро](https://github.com/antonshapiro)
[Василий Фролов](https://github.com/Vas0017)
[Мария - ShunyaBo](https://github.com/ShunyaBo)
___
[*Вверх*](#Content)
