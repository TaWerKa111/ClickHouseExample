# ClickHouse (СH) Examples
____
## Описание
Проект содержит в себе различные примеры использования Clickhouse:
- Запуск ClickHouse
- Возможность отправки запросов к ClickHouse
- Взаимодействие с ClickHouse из python
- Запуск ClickHouse в докере
- Подключение ClickHouse к rabbitMQ

## Структура
Проект содержит следующие папки:
- ClickHouseIntro: содержит основные примеры взаимодействия с ClickHouse.
- PythonAndClickHouse: содержит способы отправки в ClickHouse из python
- RabbitAndClickHouse: содержит пример использования ClickHouse и RabbitMQ

## Установка
Подробная инструкция по установке описана на официальном сайте 
ClickHouse: https://clickhouse.com/docs/ru/getting-started/install

## Запуск
В данном проекте запуск ClickHouse осуществляется по средством docker-compose.


### Запуск через docker-compose
Для запуска необходимо прописать команду. 
Параметр __"-d"__ нужен для того, чтобы запустить контейнер в фоне.
```bash
docker-compose up -d
```

### Просмотр запущенных контейнеров
Посмотреть список запущенных контейнеров можно с помощью следующей команды.
```shell
docker-compose ps
```

### Приостановка контейнера
Для приостановки работы контейнера нужно ввести следующую команду.
```shell
docker-compose stop
```


## Поддержка
____
Электронная почта для связи gleb@hiddenteam.ru

## Полезные материалы
- Документация по ClickHouse: https://clickhouse.com/docs/ru
- Статьи на habr: https://habr.com/ru/company/yandex/blog/303282/
- YouTube канал: https://www.youtube.com/c/ClickHouseDB/featured
