# trip-crawler

```
python -m venv .venv

source .venv/bin/activate
source .venv/Scripts/activate

pip install scrapy

scrapy startproject trip_crawler
cd trip_crawler

pip install -r requirements.txt



"C:\Program Files\PostgreSQL\17\bin\psql.exe" -U postgres
CREATE DATABASE scrapingdb;

scrapy crawl tripCrawler
-----------------------------------------

docker exec -it postgresDB_container psql -U aa_nadim

____________________________________________________
all---> 

pytest --cov=trip_crawler tests/

pytest --cov=trip_crawler tests/ --cov-report=html

--------------------
pytest --cov=trip_crawler tests/test_database_manager.py
pytest --cov=trip_crawler tests/test_spider.py



pytest --cov=trip_crawler tests/test_models.py

pytest --cov=trip_crawler tests/test_pipeline.py

```

pytest --cov=trip_crawler tests/conftest.py