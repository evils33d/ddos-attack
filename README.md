# ddos-atack
Este script está hecho solo para hacer pruebas de la seguridad de sitios y no para realizar acciones que puedan perjudicar a otros.

Para comenzar a trabajar te recomiendo iniciar el ambiente. Esto dependerá de que versión de python tengas:

$python3 -m venv env

$source env/bin/activate

Luego de iniciar el ambiente, debes instalar las librerias

$pip install -r requirements.txt

Hay una sola librería por lo que no debería demorar mucho.

Para usar el script ejecuta lo siguiente:

$python main.py "http://my-url.com" 50

el primer argumento del script es la url a atacar y el segundo es la cantidad de solicudes que se enviaran a dicha url.

Eso es todo!
