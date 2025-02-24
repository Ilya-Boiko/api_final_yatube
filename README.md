# API для Yatube

API для социальной сети Yatube. Позволяет пользователям создавать посты, комментировать их и подписываться на других авторов.

## Как запустить проект

1. Клонировать репозиторий и перейти в него в командной строке:
```
git clone https://github.com/Ilya-Boiko/api_final_yatube.git
```

```
cd api_final_yatube
```

2. Создать и активировать виртуальное окружение:
```
python -m venv venv
```
```
source venv/Scripts/activate
```
3. Установить зависимости:
```
pip install -r requirements.txt
```
4. Выполнить миграции:
```
python manage.py migrate
```
6. Запустить проект:
```
python manage.py runserver
```
