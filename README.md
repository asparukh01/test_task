# Testing

## Для запуска проекта:

* Для запуска проекта склонируйте его. Командой git clone.

* Затем создайте виртуальное окружение venv. Командой python3.8 -m venv venv.

* После запустите окружение. Вот так source venv/bin/activate

* Теперь надо установить зависимости, которые находятся в файле requirements.txt. Командой pip install -r requirements.txt

* Применим миграции python3.8 manage.py migrate

* Надо поставить фикстуры командой python3.8 manage.py loaddata fixtures/dump.json.

* И теперь просто запускаем проект python3.8 manage.py runserver

* Для тестирования запросов можете перейти по url http://127.0.0.1:8000/swagger/ или http://127.0.0.1:8000/redoc/

## Использовал:
* Python3.8
* Postgresql
* Django
* DRF
