FROM continuumio/miniconda3
RUN apt-get update && apt-get install -y git

RUN pip install pandas numpy sklearn mlflow psycopg2-binary

COPY train.py home/train.py