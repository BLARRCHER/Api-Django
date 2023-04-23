# Инструкция по запуску:
	## 1. Перейти в директорию "\docker+nginx+api\source", оттуда запустить docker-compose up --build;
	## 2. Зайти в bash оболочку контейнера с django(source_service_1), накатить миграции(python manage.py migrate), 
	## и собрать статику(python manage.py collectstatic)

# Описание структуры:

# 1. `django_api` — реализация API для выдачи информации о фильме.

