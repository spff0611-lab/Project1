# Data Modeling I

## Getting Started

```sh
python -m venv ENV
source ENV/bin/activate
pip install -r requirements.txt
```

### Prerequisite when install psycopg2 package

For Debian/Ubuntu users:

```sh
sudo apt install -y libpq-dev
```

For Mac users:

```sh
brew install postgresql
```

## Running Postgres

```sh
docker-compose up
```

To shutdown, press Ctrl+C and run:

```sh
docker-compose down
```

## Running ETL Scripts

```sh
python create_tables.py
python etl.py
``` 


# pip install package
1. Docker run -p 8080: 80 nginx set port 8088.this post is a local host.
    run on the web-used
    close the web- user = ctl + c
    