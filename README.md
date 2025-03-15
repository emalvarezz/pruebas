## Descripcion
Este proyecto es un juego de combate en Python, en el se enfrentan personajes hasta que se queden sin vida, en este pueden defenderte, atacar, y curarse.

## Requisitos
Para ejecutar este juego, se necesita tener instalado python 3x, en caso de no tenerlo puede descargarlo desde la pagina oficial (https://www.python.org/downloads/), tambien recomiendo el uso de un entorno virtual.

## Librerias necesarias
En este proyecto se utiliza la libreria random de python la cual genera valores aleatorios de combate.

## Instalacion 

    **  1. Clona el repositorio: **

        bash
        git clone https://github.com/emalvarezz/juego_combate
        cd JuegoCombate
        Crea un entorno virtual (opcional pero recomendado):

        En Linux/Mac:

        bash
        python3 -m venv venv
        source venv/bin/activate
        En Windows:

        bash
        python -m venv venv
        venv\Scripts\activate
    ** 2. Instala las dependencias: **

        Con el entorno virtual activado, ejecuta:

        bash
        pip install -r requirements.txt

    ** 3. Ejecuta el juego: **

        Para comenzar el combate, ejecuta el archivo main.py:

        bash
        python src/main.py
