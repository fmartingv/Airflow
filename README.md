# Airflow

Descripción del proyecto
docker-compose.yml:
Archivo de configuración para Docker Compose que define los servicios necesarios para ejecutar Airflow en un entorno Docker.

Dockerfile:
Dockerfile:
Archivo Docker que define los pasos para construir una imagen de Docker con Apache Airflow y copiar los DAGs al contenedor.

prueba.py:
Script de Python utilizado para realizar pruebas. Este script contiene una función de suma y una prueba unitaria para verificar su funcionamiento.

dags/test.py:
Archivo Python que contiene un DAG (Directed Acyclic Graph) de Airflow para la ejecución de tareas automatizadas. Define un DAG simple con un operador dummy.

Uso:
