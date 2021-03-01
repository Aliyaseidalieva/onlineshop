Репозиторий интернет-магазина
Установка:

Открыть терминал или консоль и перейти в нужную Вам директорию
Прописать команду git clone

Прописать следующие команды:

python3 -m venv env
source env/bin/activate
<<<<<<< HEAD
Перейти в директорию onlineshopwithtemplates
=======
Перейти в директорию onlineshop
>>>>>>> 1865d80f46f81f1374fb15aaeb8472eb95367d84

pip install -r req.txt
python manage.py makemigrations
python manage.py migrate

Запустить сервер - python manage.py runserver
