FROM python:3.9.5-slim

#Working directory
WORKDIR /app

# Environ
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

# Dependencies
COPY requirements.txt .
RUN pip install -r requirements.txt

# project
COPY . .