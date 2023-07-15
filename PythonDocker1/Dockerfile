FROM python:3.11.4-bookworm
LABEL authors="Rezwanul Islam"
WORKDIR /app

RUN pip3 install poetry
RUN poetry config virtualenvs.create false

COPY pyproject.toml pyproject.toml
RUN poetry install --no-dev

COPY definitions.py definitions.py
COPY app.py app.py

ENTRYPOINT ["python", "app.py"]