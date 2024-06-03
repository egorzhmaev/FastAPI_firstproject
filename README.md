# Курс по FastAPI от Артёма Шумейко
### [Ссылка на YouTube курс](https://www.youtube.com/playlist?list=PLeLN0qH0-mCVQKZ8-W1LhxDcVlWtTALCS)  

Библиотеки: alembic, sqlalchemy, fastapi-users, fastapi-cache, celery, redis, jinja.

Технологии: аутентификация пользователей (fastapi-users), кэширование запросов (redis), отложенные задачи (celery + redis), тестирование (pytest).

## Пройденные темы
1. [Эндпоинты, Параметры Пути и Запроса](https://youtu.be/O627QJxlFko)
2. [Валидация данных с Pydantic](https://youtu.be/06l4r-p-qfU)
3. [Базы данных и миграции Alembic](https://youtu.be/hO7b4yh-Qfs)
4. [Регистрация и Авторизация Пользователей](https://youtu.be/nfueh3ei8HU)
5. [Роутеры и Файловая Структура](https://youtu.be/1Ag3RoOjNI0)
6. [Проектирование REST API](https://youtu.be/-RLXmoQ7iSE)
7. [Кэширование через redis](https://youtu.be/t4H25XJG0Uc)
8. [Фоновые задачи с Celery, Redis и Flower](https://youtu.be/fm4LTvMyiwE)
9. [Тестирование API с pytest и pytest-asyncio](https://youtu.be/4xJGQKfN3ZM)
10. [Связываем Фронт и Бэк: CORS и Middleware](https://youtu.be/h0eTzi5Geo8)
11. [Верстка с Jinja. Как украсить API](https://youtu.be/AKLzDJ6XLCc)
12. [Вебсокеты (онлайн-чат)](https://youtu.be/uWSdWJEFd0Y)
13. [Depends зависимости](https://youtu.be/qvzQWBEBHYw)
14. [Docker и Docker Compose](https://youtu.be/_1H1qsNqxwM)
15. [Деплой приложения](https://youtu.be/OxE2UGHPOA0)

## Инструкция
Для локального тестирования необходимо создать виртуальное окружение командой `python3 -m venv venv` и активировать его. Команда `venv\Scripts\activate.bat` - для Windows; `source venv/bin/activate` - для Linux и MacOS.

Сколнировать репозиторий `git clone <название репозитория>` и установить зависимости командой `pip install -r requirements.txt`.

Заполнить переменные окружения в .env-non-dev

Запуск через Docker `docker compose build`, `docker compose up`

После этого можно зайти в браузере по адресу `http://localhost:9999/docs` для просмотра доступных эндпоинтов.

![pic](https://github.com/egorzhmaev/FastAPI_firstproject/blob/master/2024-06-03_22-05-05%20(1).png)
