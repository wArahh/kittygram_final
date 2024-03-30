 - [wArahh](https://github.com/wArahh)

#Kittygram
Данный проект это соц сеть для котиков. Здесь вы можете опубликовать своего кота, посмотреть на других и вынести полезные лайфхаки других хозяев.

##Стек
-DRF
-Nginx
-Docker
-Gunicorn

##Как развернуть проект
- Скачайте docker-compose.yml
- Создайте файл .env
- Создайте файл с переменными окружения

##Заполнение .env
POSTGRES_USER=<username>
POSTGRES_PASSWORD=<password>
POSTGRES_DB=<postges_db>
DB_HOST=<db_host>
DB_PORT=<db_ports>
ALLOWED_HOSTS=<hosts>
DEBUG=<True/False>
DATABASES=<POSTGRES/SQLITE>


