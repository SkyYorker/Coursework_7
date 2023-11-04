# Название проекта: todolist

## Описание проекта
Проект todolist представляет собой веб-приложение, разработанное с использованием Django и PostgreSQL. Он предоставляет пользователю возможность ...

## Стек технологий
- Python 3.9
- Django
- PostgreSQL

## Как запустить проект
1. Установите все зависимости, выполнив команду:
   
   pip install -r requirements.txt
   

2. Создайте файл .env в корневой директории проекта и заполните его следующими переменными:
   
   SECRET_KEY=your_secret_key
   DATABASE_NAME=your_database_name
   DATABASE_USER=your_database_user
   DATABASE_PASSWORD=your_database_password
   DATABASE_HOST=your_database_host
   DATABASE_PORT=your_database_port
   

3. Выполните миграции, чтобы создать необходимые таблицы в базе данных:
   
   python manage.py migrate
   

4. Запустите проект, выполнив команду:
   
   python manage.py runserver
   

5. Теперь вы можете открыть приложение в браузере по адресу http://localhost:8000/.

Убедитесь, что у вас установлен Python 3.9 и PostgreSQL перед запуском проекта.
