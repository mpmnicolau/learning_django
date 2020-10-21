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


Durante a aula em 21/10/2020, o caminho para executar django passa por:

criar modulo serie: python manage.py startapp serie
startar o server
criar o template para serie: copiar do git
adicionar o modulo de serie no settings do modulo principal
registrar a url
criar o arquivo serie/urls e codificar
criar aa model de serie
criar o form de serie
incluir a model no admin de serie
criar tabela -python manage.py makemigrations serie

startar o server


Na aula, foi citado o github de exemplo do https://github.com/brigolini
