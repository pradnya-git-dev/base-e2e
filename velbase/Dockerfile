# syntax=docker/dockerfile:1
FROM python:3
ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1
WORKDIR /usr/src/velbase
COPY requirements.txt /usr/src/velbase/
RUN pip install -r requirements.txt
COPY . /usr/src/velbase/