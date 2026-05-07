FROM python:3.11-slim

WORKDIR /app
COPY . .

RUN pip install -r /app/app_python/requirements.txt

CMD ["python", "app.py"]

