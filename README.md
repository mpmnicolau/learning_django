# learning_django

python -m pip install --user virtualenv
bootmgr
dentro da pasta do projeto:
py -m venv showsenv
.\showsenv\Scripts\activate
python -m pip install Django
django-admin startproject igtiflixweb
cd igtiflixweb
python manage.py runserver
python manage.py startapp principal
python manage.py migrate (para criar as estruturas de banco - fiz isso depois de criar os forms)
python manage.py createsuperuser (para acesso aos bancos)
python manage.py makemigrations genero (para executar a migration)
python manage.py migrate
python manage.py runserver
