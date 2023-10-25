# course

# Окружение для тестового поднятия Linux

## Установка Docker Linux
- sudo apt install git
- sudo apt  install docker-compose
- sudo usermod -aG docker ${USER}

## Скачивание проекта
- git clone https://github.com/malverdo/course.git

## Подготовка Docker
- `docker-compose build` # Сборка
- `docker-compose up -d` # Первый запуск в режиме dev


## Команды docker-compose
- `docker-compose start` # Старт контейнеры
- `docker-compose stop` # Стоп контейнеры
- `docker-compose down` # Стоп и удалить контейнеры

## Зайти в контейнер
- docker exec -it php bash

## Адреса 
- http://localhost:2095/ # главная страница index.php
- PgAdmin
  - http://172.17.0.1:16543/
  - test@mail.ru # login
  - test@mail.ru # password
- Подключиение к БД
  - 172.17.0.1 or localhost # address
  - 54321 # port
  - postgres # user
  - root # password