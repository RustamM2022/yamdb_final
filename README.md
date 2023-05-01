Отображение статуса workflow:

![example workflow](https://github.com/RustamM2022/yamdb_final/actions/workflows/yamdb_worklows.yml/badge.svg)



# Установка
Клонировать репозиторий:

git clone git@github.com:RustamM2022/yamdb_final.git
Измените свою текущую дерикторию потребления:

cd /yamdb_final/
создавать и активировать окружающую среду

python -m venv venv
source venv/scripts/activate

Создайте файл .env с переменными окружения для работы с базой данных по следущему шаблону:
- DB_ENGINE=django.db.backends.postgresql # указываем, что работаем с postgresql
- DB_NAME=postgres # имя базы данных
- POSTGRES_USER=postgres # логин для подключения к базе данных
- POSTGRES_PASSWORD=postgres # пароль для подключения к БД (установите свой)
- DB_HOST=db # название сервиса (контейнера)
- DB_PORT=5432 # порт для подключения к БД 

# Запуск приложения в контейнерах на Windows:
запустите программу Docker Destkop
в командной строке git bash выполните: 
- docker-compose up -d --build


Полная документация проекта (redoc) доступна по адресу http://130.193.41.207/redoc/
