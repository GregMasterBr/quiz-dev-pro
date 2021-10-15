Python PRO - Jornada Rumo a Primeira Vaga - Sistema QUIZ DEV Pro - Renzo - Ed - Março 2021 - https://www.youtube.com/c/PythonProBr

mkdir pasta

python -m venv/venv

venv\Scripts\Activate.ps1

pip install django

django-admin startproject quiz .

#verificar se instalou
python manage.py runserver

#criando um app

/[dir]> python manage.py startapp base

no settings.py adicionar o app que foi instalado.

python manage.py makemigrations (aplicar nossas models no banco)

python manage.py migrate

python manage.py createsuperuser


 
