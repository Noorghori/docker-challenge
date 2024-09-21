FROM python:3.9-slim

WORKDIR /usr/src/app

COPY scraper.py .

RUN pip install psutil flask

CMD ["python", "scraper.py"]
