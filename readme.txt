## Название проекта

### Описание проекта (зачем нужен? что можно делать?)

Здесь иконки тезнологий , можно убрать , но если хочется красиво оформить ридми, то можно выбрать подходящие и убрать лишние

[![Python](https://img.shields.io/badge/-Python-464646?style=flat-square&logo=Python)](https://www.python.org/)
[![Django](https://img.shields.io/badge/-Django-464646?style=flat-square&logo=Django)](https://www.djangoproject.com/)
[![Django REST Framework](https://img.shields.io/badge/-Django%20REST%20Framework-464646?style=flat-square&logo=Django%20REST%20Framework)](https://www.django-rest-framework.org/)
[![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-464646?style=flat-square&logo=PostgreSQL)](https://www.postgresql.org/)
[![Nginx](https://img.shields.io/badge/-NGINX-464646?style=flat-square&logo=NGINX)](https://nginx.org/ru/)
[![gunicorn](https://img.shields.io/badge/-gunicorn-464646?style=flat-square&logo=gunicorn)](https://gunicorn.org/)
[![docker](https://img.shields.io/badge/-Docker-464646?style=flat-square&logo=docker)](https://www.docker.com/)

### Технологии: УБРАТЬ ЛИШНИЕ ИЛИ ДОБАВИТЬ НЕОБХОДИМЫЕ
- python 3.11
- django 4.2.2
- djangorestframework 3.14.0
- nginx
- gunicorn
- PostgreSQL
- Docker

### Инструкция для развертывания проекта с использованием Docker:

Если  docker не используется в проекте, то стоит указать шаги с командами для выполнения по примеру ниже:
1. Клонирование
2. Создание и активация виртуального окружения
3. Установка зависимостей
4. Запуск проекта
5. Если используются технологии , которые требуют дополнительных команд для запуска (например celery) - указать команды для их запуска

Клонирование проекта:
```
git clone https://github.com/A1exit/SKYTEST
```
Запуск:

Для запуска проекта необходимо создать .env в директории (тут корневая директория вашего проекта),
скопировать в него содержимое файла  .env.example

Запустить команду, указанную ниже из директории (тут директория с docker-compose.yaml)
```
docker-compose up -d --build
```

### Автор проекта:
ФИО или ссылка на гитхаб