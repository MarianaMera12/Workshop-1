# Workshop - 001 
*By:* Mariana Mera Gutierrez 

Intro 


Tools Used 

Lenguajes de programación: Python
Entorno de desarrollo: Jupyter Notebook
Base de datos: Postgres
Herramienta de Business Intelligence: Power BI


### Data

I have 50k rows of data about candidates. The fields we will use are:

- First Name
- Last Name
- Email
- Country
- Application Date
- Yoe (years of experience)
- Seniority
- Technology
- Code Challenge Score
- Technical Interview

About repository
Acerca del repositorio:

Este repositorio contiene los scripts y archivos necesarios para completar el desafío.

La estructura del repositorio es la siguiente:
README.md: Este archivo que estás leyendo ahora.
scripts: Carpeta que contiene los scripts de Python para cargar los datos a la base de datos y realizar análisis adicionales (si es necesario).
notebooks: Carpeta que puede contener notebooks de Jupyter adicionales para realizar Exploratory Data Analysis (EDA) o visualizaciones iniciales.
data: Carpeta que contendrá el archivo CSV con los datos del candidato (debes agregar el archivo aquí).
requirements.txt: Archivo que especifica las dependencias de Python necesarias para ejecutar el proyecto.

Requerimientos 
Variables de entorno:

Para conectarte a la base de datos, deberás configurar algunas variables de entorno. Deberás crear un archivo .env (que se ignora en el control de versiones) y agregar las siguientes variables:

HOST=localhost
DATABASE=desafio_data_engineer
USER=your_username
PASSWORD=your_password
Reemplaza your_username y your_password con las credenciales de tu base de datos.



Run this project 
Clona este repositorio.
Instala las dependencias de Python ejecutando pip install -r requirements.txt en la terminal.
Crea y configura el archivo .env con tus credenciales de la base de datos.
Ejecuta los scripts de Python en la carpeta scripts para cargar los datos a la base de datos.
Conecta la base de datos a Power BI Desktop.
Crea un dashboard en Power BI con las visualizaciones especificadas.
Consulta la sección de Agradecimientos para ver cualquier reconocimiento.

Database Postgres
Base de datos Postgres:

Este proyecto utiliza Postgres como base de datos de ejemplo. Deberás crear una base de datos y un usuario con los permisos necesarios para ejecutar las consultas. Los scripts de Python se encargarán de crear las tablas necesarias en la base de datos.

About EDA 

Connection Power BI 
Conexión a Power BI:

Deberás conectar Power BI Desktop a la base de datos Postgres para poder acceder a los datos del candidato. Sigue las instrucciones de Power BI para crear una conexión de base de datos.

Dashboard

Agradecimientos
