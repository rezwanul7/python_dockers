FROM python:3.11.4-bookworm
LABEL authors="Rezwanul Islam"
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY definitions.py definitions.py
COPY app.py app.py
ENTRYPOINT ["python", "app.py"]