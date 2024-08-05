FROM python:3.10-slim

ENV PYTHONBUFFERED=1

WORKDIR /backend

COPY . .

RUN pip install -r requirements.txt

EXPOSE 8000