FROM python:3.9.2-slim

WORKDIR /app
COPY . /app

RUN pip install -r requirements.txt

CMD ["python3", "metrics-request.py"]