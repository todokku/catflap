FROM python:3.8

WORKDIR /app

COPY . ./

RUN pip install --upgrade pip && \
    pip install poetry
RUN poetry install
