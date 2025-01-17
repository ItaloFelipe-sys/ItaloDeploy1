## Requisitos

* Python 3 ou superior - conferir a versão = python --version

## sequência para criar o projeto
* criar o ambiente virtual

$ python -m venv venv

Ativar ambiente virtual.

$ venv\Scripts\Activate

Instalar o Django.

$ pip install Django

Criar o projeto do Django.

$ django-admin startproject admin .

gerar o arquivo com as dependências.
Após instalar a dependência, execute o comando abaixo.

$ pip freeze > requirements.txt

Executa as migration.

$ python manage.py migrate

Rodar o projeto.

$ python manage.py runserver

http://127.0.0.1:8000/

Criar um super usuário.

$ python manage.py createsuperuser

Usuário (leave blank to use 'italo'): admin
Endereço de email: It4l0f5l1pe@gmail.com
Password: 2911
Password again: 2911

Acessar o sistema administrativo padrão do Python.

http://127.0.0.1:8000/admin

Criar um novo app.

$ python manage.py startapp nome-do-app

$ python manage.py startapp italo





