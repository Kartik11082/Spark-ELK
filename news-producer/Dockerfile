FROM python:3.9-slim

WORKDIR /app

COPY newsapi_producer.py .

RUN pip install kafka-python requests

CMD ["python", "newsapi_producer.py"]
