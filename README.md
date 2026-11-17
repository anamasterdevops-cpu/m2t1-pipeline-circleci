# m2t1-pipeline-circleci

Parte A de la Tarea 1 del Módulo 2 (Máster en Desarrollo Seguro DevSecOps).

Pipeline de integración continua (CI) con **CircleCI** a partir de los ficheros del campus:

- `saludar.py`: aplicación sencilla que imprime un saludo al azar.
- `test_saludar.py`: pruebas con **pytest**.
- `requirements.txt`: dependencias (pytest, flake8...).
- `.circleci/config.yml`: configuración del pipeline. En cada push, CircleCI descarga el código,
  instala las dependencias y ejecuta flake8 y pytest.
- `Dockerfile`: imagen de ejemplo del campus (en esta parte no se construye).
