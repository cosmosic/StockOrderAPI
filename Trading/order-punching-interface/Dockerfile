FROM python:3.9.19-slim-bullseye

RUN apt-get update && apt-get upgrade -y

WORKDIR /app

COPY . /app/

ADD /home/shree/algotest_assignment/crud /app/crud

RUN pip install -r requirement.txt

RUN pip install -e ./crud