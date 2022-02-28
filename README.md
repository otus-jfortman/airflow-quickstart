# Airflow Quick Start

Airflow Quick Start using Docker Compose

## Usage

### Initialize the Airflow DB
```bash
npm run init
```

### Run Airflow Containers
```bash
npm start

# same as
docker-compose up -d
```

### Web UI
Web UI for Airflow can be reached at [http://localhost:8080](http://localhost:8080)

#### Admin account:
username: `airflow`  
password: `airflow`

## Sources
[Running Airflow in Docker](https://Airflow.apache.org/docs/apache-airflow/stable/start/docker.html)