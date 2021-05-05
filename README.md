# CRUD CON FASTAPI, SQLALCHEMY Y MYSQL

## PASOS PARA INSTALAR
1. Crear un ambiente virtual con Python3
```
virtualenv env -p python3

```
2. Activar el ambiente virtual
```
source env/bin/activate

```
3. Instalar las librerías necesarias que se encuentran en el archivo requirements.txt
```
pip install -r requirements.txt

```

## DESPLEGANDO EL AMBIENTE
```
uvicorn main:app --reload

```
* main es el nombre del archivo main.py
* app es el nombre de la variable de FASTAPI inicializada en el archivo main


