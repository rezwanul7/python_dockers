FROM python:3.11.4-bookworm
WORKDIR /app
RUN pip install numpy
COPY definitions.py definitions.py
COPY app.py app.py
CMD ["python","app.py"]