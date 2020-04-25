# Repositorio orientado para todos los cursos de Data Science con python

Para la creacion de carpeta por proyecto/curso se hace a través de cookiecutter, por lo tanto
es necesario ejecutar los siguientes comandos

    > python37 -m pip install virtualenv
    > python37 -m virtualenv .venv
    > source .venv/Scripts/activate
    > pip install cookiecutter
    > cookiecutter https://github.com/drivendata/cookiecutter-data-science
    > pip install -r requeriments.txt