FROM python:3.10

WORKDIR /app

COPY requirements.txt requirements.txt

RUN pip install -r requirements.txt

COPY pipeline.py pipeline.py

# ENTRYPOINT [ "bash" ]
ENTRYPOINT [ "python","pipeline.py" ]