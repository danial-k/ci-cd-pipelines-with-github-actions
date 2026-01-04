FROM python:3-slim

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY src/ .

CMD ["fastapi", "dev", "main.py", "--host", "0.0.0.0"]
