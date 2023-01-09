# Webservice REST com Django Rest Framework

[![Python](https://img.shields.io/badge/Python-v3.11-blue)](https://www.python.org/downloads/release/python-3111/)
[![Django](https://img.shields.io/badge/Django-v4.1.5-orange)](https://docs.djangoproject.com/en/4.1/)
[![Django REST framework](https://img.shields.io/badge/Django_Rest_Framework-v3.14.0-red)](https://www.django-rest-framework.org/)

## Estrutura do projeto

- Projeto criado com o Django
- `config` módulo com configurações do projeto
- `escola` modulo com entidades do dominio escola

## Djando REST API
```bash
# criação de um virtualenv
python3 -m venv ./venv

# ativando venv Windows
.\venv\Scripts\activate

# ativando venv Linux/Mac
source /bin/scripts/activate

# instalando dependencias
pip install -r requires.txt

#executando migrations
python manage.py migrate

#criação do super usuário para o admin
python manage.py createsuperuser

# executando servidor
python manage.py runserver
```

## Requisitos

```python
asgiref==3.6.0
Django==4.1.5
djangorestframework==3.14.0
pytz==2022.7
sqlparse==0.4.3
```
