FROM python:3.10.11-slim-buster

WORKDIR /app

COPY backend_rds/requirements.txt .
COPY backend_rds/wait_for_postgres.sh .
RUN chmod +x wait_for_postgres.sh

RUN pip install --no-cache-dir -r requirements.txt

COPY . .

CMD ["./wait_for_postgres.sh"]
