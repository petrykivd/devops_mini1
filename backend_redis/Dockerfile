FROM python:3.10.11-slim-buster

WORKDIR /app

COPY backend_redis/requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY . .
