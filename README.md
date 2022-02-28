# Airflow Quick Start

Airflow Quick Start using Docker Compose

## Usage

### Initialize the Airflow DB
```bash
npm run init
```
#### This creates an admin account:
username: `airflow`  
password: `airflow`

### Run Airflow Containers
```bash
npm start

# same as
docker-compose up -d
```

### Web UI
Web UI for Airflow can be reached at [http://localhost:8080](http://localhost:8080)

## Sources
[Running Airflow in Docker](https://Airflow.apache.org/docs/apache-Airflow/stable/start/docker.html)