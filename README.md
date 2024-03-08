# Workshop-001 

## By: Mariana Mera Gutierrez 

### Candidate Data Analysis Challenge: Visualizing the Results

This project focuses on the analysis and visualization of data from candidates who participated in selection processes. Starting from a CSV file with randomly generated information, the main objective is to:

**Perform analysis and manipulations on the data:**

- Data exploration.
- Calculation of relevant metrics.
- Identification of patterns and trends in the data.

**Visualize data in an attractive and informative way:**

- Creation of interactive graphs and dashboards.
- Communicating findings in a clear and concise manner.

### Tools Technologies

- Python 
- Jupiter Notebook
- Database PostgreSQL
- Power BI 

### Data

The dataset has 50k records about the candidates and contains the following information:

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


### Repository content
The structure of the repository is as follows:

- `data`: Folder containing the CSV files 'candidates.csv' and 'CountryContinet.csv'.

- `README.md`: This file you are reading now.

- `EDA.ipynb`: There is the connection to the database, data processing and analysis.

- `requirements.txt`: File that specifies the Python dependencies required to run the project.

### Requirements
- Install Python : [Python Downloads](https://www.python.org/downloads/)
- Install PostgreSQL : [PostgreSQL Downloads](https://www.postgresql.org/download/)
- Install Power BI : [Power BI Desktop](https://www.microsoft.com/en-us/download/details.aspx?id=58494) 

### Environment variables

To connect to the database, you will need to set some environment variables.

`DATABASE`: Replace with the name of the database you want to use.

`USER`: Replaces with the database user name.

`PASSWORD`: Replaces with the password of the database user.

`HOST`: Indicates the address of the PostgreSQL database server to which the application will connect.

`PORT`: PostgreSQL server listening port.

### Run this project

1. Clone the project
~~~
git clone https://github.com/MarianaMera12/Workshop-1.git  
~~~
2. Go to the project directory
~~~
cd Workshop-1
~~~
3. Create virtual environment for Python
~~~
python -m venv venv
~~~
4. Install libreries
~~~
pip install -r requirements.txt
~~~

### PostgreSQL
5. Create a database in PostgreSQL
- This project uses Postgres as an example database. You will need to create a database and a user with the necessary permissions to run the queries.

### EDA
6. The `data` folder contains the two CSVs that are implemented in this project, `candidates.csv` and `CountryContinet.csv`.

7. The `EDA.ipynb` contains the connection and the creation of the tables, as well as the necessary analysis to understand the data set.

### Power BI

8. We made the connection with Power BI to graph the transformed data.

 - Open a new window in Power BI
 [![Datos.png](https://i.postimg.cc/fRFZQdzD/Datos.png)](https://postimg.cc/RWc2cNJD)


 - Select in 'more'

 [![datas2.png](https://i.postimg.cc/JzdJwpH0/datas2.png)](https://postimg.cc/w1L3LcVY)

 
 - Select PostgreSQL database

 [![datos3.png](https://i.postimg.cc/sfNRhSWS/datos3.png)](https://postimg.cc/K4BVX1Jv)

 
 - Insert your information and accept

 [![datos4.png](https://i.postimg.cc/j2G9kH6F/datos4.png)](https://postimg.cc/T5JCKW4V)

 
 - Select the table and download the information

   
[![datosfinally.png](https://i.postimg.cc/6QcQJ3m0/datosfinally.png)](https://postimg.cc/d77FGqvk)

Already the data is synchronized with Power BI and you can make your own dashboard.

### Dashboard
[![Workshop-One-page-0002.jpg](https://i.postimg.cc/fyL0yPP6/Workshop-One-page-0002.jpg)](https://postimg.cc/ftGbg8DK)

[![Workshop-One-page-0003.jpg](https://i.postimg.cc/RCsHyM69/Workshop-One-page-0003.jpg)](https://postimg.cc/dDC3TcjS)

If you want to interact with my dashboard, [Click!](https://app.powerbi.com/view?r=eyJrIjoiNTQ4NDhiMjQtMjUyNS00MDQ0LTgwYTgtODc2Zjk4YzY5NTE0IiwidCI6IjY5M2NiZWEwLTRlZjktNDI1NC04OTc3LTc2ZTA1Y2I1ZjU1NiIsImMiOjR9). 


### Thank you for visiting our repository!

We hope this project will help you practice your Data Engineer skills. If you found it useful, give it a star!

Your comments and suggestions are welcome, please contribute to the project!

See you soon... 

