# Проект 9-го спринта

### Структура репозитория

- pics - картинки для README
- ddl - структура таблиц в хранилище PostgreSQL
- commands - команды для работы с Kafka и Redis

### Описание проекта

В этом проекте необходимо реализовать два оставшихся сервиса, которые заполняют слои DDS и CDM, а именно:

- Организовать сбор данных из разных источников (Kafka и Redis) о транзакционной активности пользователей
- Реализовать доставку данных в хранилище и их распределение по слоям для последующего использования данных из витрины слоя CDM для построения итогового дашборда

<ссылка на первую картинку>

Полная архитектура решения выглядит так:

<ссылка на первую картинку>


### Используемые инструменты

- Yandex Cloud
- Docker
- Kubernetes
- Apache Kafka
- Redis
- PostgreSQL
- Python
- SQL
- Bash
