# 📌 Projeto Django

Projeto web desenvolvido utilizando o framework Django.

---

Tecnologias utilizadas:
* Python
* Django
* HTML
* CSS
* SQLite

---

## ⚙️ Como criar o ambiente virtual

```bash
# Criar ambiente virtual
python -m venv venv

# Ativar no Windows
venv\Scripts\activate

# Ativar no Linux/Mac
source venv/bin/activate

# Instalar dependências
pip install django
```

---

## 🚀 Como criar um projeto Django do zero

```bash
# Criar projeto
django-admin startproject meu_projeto

# Entrar na pasta
cd meu_projeto

# Rodar o servidor
python manage.py runserver
```

Acesse no navegador:

```
http://127.0.0.1:8000/
```

---

## 📦 Como criar um app dentro do projeto

```bash
python manage.py startapp meu_app
```

Depois, adicione o app no arquivo `settings.py`:

```python
INSTALLED_APPS = [
    'meu_app',
]
```

---

## 🔄 Aplicar migrações

```bash
python manage.py makemigrations
python manage.py migrate
```

---

## 👤 Criar superusuário (admin)

```bash
python manage.py createsuperuser
```

Acesse:

```
http://127.0.0.1:8000/admin/
```

---

## ▶️ Como rodar o projeto

```bash
# Ativar ambiente virtual
venv\Scripts\activate  # Windows
# ou
source venv/bin/activate  # Linux/Mac

# Rodar servidor
python manage.py runserver
```

---

## 📁 Estrutura básica do projeto

```
meu_projeto/
│
├── meu_projeto/
│   ├── settings.py
│   ├── urls.py
│   └── asgi.py / wsgi.py
│
├── meu_app/
│   ├── models.py
│   ├── views.py
│   ├── admin.py
│   └── migrations/
│
├── manage.py
```

