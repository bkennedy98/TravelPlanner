FROM mcr.microsoft.com/devcontainers/python:0-3.11

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt

WORKDIR /app/django_app

EXPOSE 8000

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]