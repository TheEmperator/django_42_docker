FROM python:3.11-slim

RUN apt update
RUN apt upgrade -y
RUN apt install -y build-essential
RUN apt install -y libpq-dev python3-dev

RUN python -m pip install --upgrade pip

COPY requirements.txt requirements.txt
RUN python -m pip install -r requirements.txt

COPY . .
