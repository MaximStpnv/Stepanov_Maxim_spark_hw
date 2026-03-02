# Домашняя работа по Spark

## Окружение

Apache Spark запускался локально с использованием Docker.  
Использован официальный образ `jupyter/pyspark-notebook`.

Spark работает в режиме `local[*]` внутри одного контейнера.

## Структура проекта

- `docker-compose.yaml` — конфигурация для запуска Jupyter + Spark
- `notebooks/` — папка, смонтированная в контейнер
- `notebooks/task.ipynb` — ноутбук с выполненным заданием
