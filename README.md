
## Pasos realizados

mkdir python-final
cd python-final
git init
touch finales.py
code .
python -V
python3 -V
python3 -m venv venv
source venv/bin/activate
python -m venv venv
venv\Scripts\activate
python -m pip install --upgrade pip

git add .
git commit -m "Primer commit: estructura del proyecto y entorno virtual creado"
git remote add origin https://github.com/nawe2/python-final.git
git branch -M main
git push -u origin main


## ¿Qué es pip y por qué lo actualizamos?

PIP es el administrador de paquetes de python, esencial para instalar, actualizar y eliminar módulos y bibliotecas en los proyectos. Es importante actualizar PIP para acceder a nuevas funciones, correcciones de errores y mejoras de seguridad, también para asegurar la compatibilidad con los paquetes más recientes y evitar ese tipo de problemas.