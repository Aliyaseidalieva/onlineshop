Репозиторий интернет-магазина

Установка:


Открыть терминал или консоль и перейти в нужную Вам директорию


Прописать команду git clone


Прописать следующие команды:


python3 -m venv env


source env/bin/activate


Перейти в директорию onlineshop

pip install -r req.txt

python manage.py makemigrations

python manage.py migrate

Запустить сервер - python manage.py runserver
