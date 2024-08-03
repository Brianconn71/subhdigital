FROM python:3.10-slim

ENV PYTHONBUFFERED=1

WORKDIR /backend

RUN pip install -r requirements.txt

COPY . .

EXPOSE 8000