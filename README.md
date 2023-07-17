# Описание
Яндекс Практикум. Спринт 14. Финальный проект спринта: деплой проекта Kittygram на удалённый сервер

# Функционал
- Позволяет регистрироваться новым пользователям;
- Добавление новых котиков;
- Указание достижений этих домашних питомцев;
- Возможность делиться своими любимцами;
# Установка
_1. Клонировать репозиторий:_
```
git clone https://github.com/Arthur-Garipov/infra_sprint1
```
_2. Перейти в папку с проектом:_
```
cd infra_sprint1/backend
```
_3. Установить виртуальное окружение для проекта:_
```
python -m venv venv
```
_4. Активировать виртуальное окружение для проекта:_

# для OS Lunix и MacOS
```
source venv/bin/activate
```
# для OS Windows
```
source venv/Scripts/activate
```
_5. Установить зависимости:_
```
python -m pip install --upgrade pip
pip install -r requirements.txt
```
_6. Выполнить миграции на уровне проекта:_
```
cd yatube
python3 manage.py makemigrations
python3 manage.py migrate
```
_7. Запустить проект:_
```
python manage.py runserver
```
# Технологии используемые в проекте:
- Python v.3.10
- HTML
- CSS
- NGINX
- Gunicorn v.20.1

# Contributors:
- https://github.com/Arthur-Garipov
- https://github.com/yandex-praktikum
