FROM python:3.11.4-bookworm
WORKDIR /app
COPY setup.py setup.py
RUN pip install .
COPY definitions.py definitions.py
COPY app.py app.py
CMD ["python", "app.py"]