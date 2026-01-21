# estrutura-padrao-django

```
django-blog/
│
├── core/                  # Configurações do projeto
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── apps/
│   ├── accounts/
│   │   ├── migrations/
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── models.py
│   │   ├── urls.py
│   │   ├── views.py
│   │   └── tests.py
│   │
│   └── blog/
│       ├── migrations/
│       ├── admin.py
│       ├── models.py
│       ├── urls.py
│       ├── views.py
│       └── tests.py
│
├── templates/
│   ├── base.html
│   ├── blog/
│   │   └── post_list.html
│
├── static/
│   ├── css/
│   └── js/
│
├── manage.py
├── .env.example
├── .gitignore
├── requirements.txt
└── README.md

```

## Padrão de Readme (Use em todos)

```
# Nome do Projeto

Descrição curta do projeto.

## Tecnologias
- Python
- Flask/Django
- SQLite/PostgreSQL

## Como rodar
1. git clone
2. python -m venv venv
3. pip install -r requirements.txt
4. python run.py / python manage.py runserver

```

## 📌 Dica profissional (muito importante)

Sempre crie um arquivo:

```
.gitignore  
```

E

```
.env.example

# adicione o seguinte conteúdo:

SECRET_KEY=your-secret-key
DEBUG=True
DATABASE_URL=sqlite:///db.sqlite3

```
