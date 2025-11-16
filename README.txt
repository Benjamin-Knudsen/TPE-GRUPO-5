======================================
README: TPE Grupo 5 - Siniestros 2022
======================================

Este repositorio contiene el Trabajo Práctico Especial (TPE) del Grupo 5, centrado en el análisis de un dataset de siniestros viales del año 2022.

--------------------------------------
Contenido del Repositorio
--------------------------------------

* TPE_Grupo_5.ipynb:    El Jupyter Notebook principal con todo el análisis de datos.
* siniestros-2022.csv:  El dataset fuente utilizado en el análisis.
* requirements.txt:     El listado de librerías de Python necesarias para ejecutar el notebook.

--------------------------------------
Prerrequisitos
--------------------------------------

Antes de comenzar, asegúrate de tener instalado lo siguiente:
1.  Python (versión 3.8 o superior).
2.  Visual Studio Code (VS Code).
3.  Extensión de Python para VS Code (esta generalmente incluye las herramientas de Jupyter Notebook).

--------------------------------------
Instrucciones de Configuración y Ejecución
--------------------------------------

Sigue estos pasos para configurar el entorno y ejecutar el proyecto en VS Code:
1.  EXTRAER EL ARCHIVO ZIP
    * Una vez descargado, debes descomprimirlo para poder usar los archivos.

    * En Windows:
        * Encuentra el archivo .zip en tu carpeta de "Descargas".
        * Haz clic derecho sobre el archivo.
        * Selecciona "Extraer todo..." (o "Extract All...").
        * Elige una ubicación (o deja la que viene por defecto) y haz clic en "Extraer".
    * En macOS:
        * Encuentra el archivo .zip en tu "Finder" (generalmente en Descargas).
        * Simplemente haz doble clic sobre el archivo. Se descomprimirá automáticamente en una carpeta con el mismo nombre

Simplemente haz doble clic sobre el archivo. Se descomprimirá automáticamente en una carpeta con el mismo nombre.
2.  ABRIR EL PROYECTO
    * Abre Visual Studio Code.
    * Ve a "Archivo" > "Abrir carpeta..." (File > Open Folder...).
    * Selecciona la carpeta donde descargaste o clonaste este repositorio.

3.  CREAR EL ENTORNO VIRTUAL (VENV)
    * Abre la terminal integrada de VS Code (menú "Terminal" > "Nuevo terminal").
    * En la terminal, escribe el siguiente comando para crear un entorno virtual. Recomendamos llamarlo ".venv" para que VS Code lo detecte automáticamente.

        python -m venv .venv

    * (Nota: Si el comando 'python' no funciona, prueba con 'python3' o 'py').

4.  ACTIVAR EL ENTORNO VIRTUAL
    * El entorno debe activarse para poder usarlo. El comando cambia según tu sistema operativo:

    * En Windows (usando PowerShell):
        .\.venv\Scripts\Activate

    * En macOS o Linux (usando bash/zsh):
        source .venv/bin/activate

    * Sabrás que está activo porque el nombre del entorno "(.venv)" aparecerá al inicio de la línea de tu terminal.

5.  INSTALAR LAS DEPENDENCIAS
    * Con el entorno virtual aún activo en la terminal, instala todas las librerías listadas en `requirements.txt` con un solo comando:

        pip install -r requirements.txt

    * Esto "reconstruirá" el ambiente de PIP exacto necesario para el proyecto.

6.  EJECUTAR EL NOTEBOOK
    * En el explorador de archivos de VS Code (el panel izquierdo), haz clic en el archivo `TPE_Grupo_5.ipynb`.
    * VS Code abrirá el notebook.
    * Arriba a la derecha, haz clic en "Seleccionar Kernel".
    * Asegúrate de seleccionar el entorno que acabas de crear (debería aparecer como "Python 3.X.X ('.venv')"). 
         (NOTA:Si no aparece.
               Opcion 1: seleccionar "Select Another Kernel..." --> "Python Enviroments..." --> "Python 3.X.X ('.venv')"
               Opcion 2: reinicia VS Code.

    * ¡Listo! Ahora puedes ejecutar todas las celdas del notebook para ver el análisis.
