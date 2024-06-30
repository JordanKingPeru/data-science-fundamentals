# Proyecto: Data Science Fundamentals

Incluye los siguientes tópicos:

* Fundamentos
* Código Git
* Código Python y R

## Configuración del Environment

Para replicar el proyecto se debe de usar Python 3.12 en un ambiente de Conda

```python
conda create --name envDataScience python=3.12
```

Tener en cuenta que se usaron las librerias de requirement.txt

```python
numpy==2.0.0
pandas==2.2.2
matplotlib==3.9.0
scikit-learn==1.5.0
psycopg2-binary==2.9.9
python-dotenv==1.0.1
pymongo==4.8.0
```

## Navegación de carpeta

El propyecto se estructura de la siguiente forma:

* 01datos: se encuentra los datos utilizados en el proceso y los resultados
* 02notebooks: se encuentra los notebooks de desarrollo y producción
  * Para producción, primero se define las variables de entorno productivos
  * Desplegar notebook acciones_comerciales.ipynb
* 03presentaciones: para actualizar el reporte ejecutar el notebook reporte_estatus.ipynb
