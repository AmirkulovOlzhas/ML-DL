FROM jupyter/scipy-notebook:2023-07-31

COPY requirements.txt requirements.txt

# RUN brew postgresql-upgrade-database

RUN pip install --upgrade pip

RUN pip install -r requirements.txt

WORKDIR /home/jovyan/work/lab
