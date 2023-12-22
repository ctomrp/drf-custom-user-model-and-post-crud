# drf-custom-user-model

## 1) Crea un entorno virtual con:
### Desde windows:
```bash
py -m venv venv
```
### Desde linux/mac:
```bash
python3 -m venv venv
```
## 2) Accede al entorno:
### Desde windows:
```bash
.\venv\Script\activate
```
### Desde linux/mac
```bash
source venv/script/activate
```
## 3) Instala poetry y luego instala las dependencias del proyecto:
```bash
pip install poetry
poetry install
```
## 4) Ejecuta las migraciones y luego el proyecto:
### Desde windows:
```bash
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
### Desde linux/mac:
```bash
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver
```