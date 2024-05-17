# Airflow

Vamos a usar con Docker Airflow para asi subir un dag y ejecutarlo desde ahi.

  1. Crearemos una carpeta donde estaran los diferentes archivos, entre ellos estarán:
  -docker-compose.yml: donde esta la configuracion como la imagen del airflow, el puerto donde accederemos y la carpeta de dags el dag de prueba:

  ![image](https://github.com/fmartingv/Airflow/assets/120713266/1704b109-f361-4459-922a-077f4bf0b977)

  -Dockerfile: Aqui ponemos que descargue la ultima imagen de Airflow y que copie los dags

  ![image](https://github.com/fmartingv/Airflow/assets/120713266/7730e065-0f82-4f69-a115-19e5bf9125a3)

  - dags/prueba.py: Creamos un dag de prueba poneindole los datos de cuando se creo y demas, lo que va a ahcer es un dummytask que en si no hace nada solo sirve como prueba.

  ![image](https://github.com/fmartingv/Airflow/assets/120713266/3caae815-0751-489f-989e-1c5b798c8a0a)


  2. Ahora hacemos el docker-compose up para asi ver el airflow y ejecutarlo:

![image](https://github.com/fmartingv/Airflow/assets/120713266/7a1f151f-8d46-4a2b-a070-7784b33544b6)

![image](https://github.com/fmartingv/Airflow/assets/120713266/696f1c7b-ffa2-499f-be33-c156c3348e74)

![image](https://github.com/fmartingv/Airflow/assets/120713266/6fc63383-a953-47a9-b7a2-73eeced08eff)
