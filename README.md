# Instalación

Primero se debe instalar pip3 si no se lo tiene todavía:

```
sudo apt update
sudo apt install python3-pip

pip3 --version
```

Luego se debe de configurar un entorno.

```
pip3 install virtualenv

mkdir fastapi
cd fastapi
python3 -m venv venv

source venv/bin/activate
```

Se puede revisar todos los paquetes instalados en el entorno

```
pip list
pip freeze > requirements.txt

pip install -r requirements.txt

deactivate
```

Para levantar Fastapi

```
fastapi dev main.py
```
