FROM jupyter/scipy-notebook:2023-07-31

COPY requirements.txt requirements.txt

# RUN brew postgresql-upgrade-database

RUN pip install --upgrade pip

RUN pip install -r requirements.txt

# USER root

# RUN localedef -i en_US -f UTF-8 en_US.UTF-8
# RUN localedef -i en_US -c -f UTF-8 -A /usr/share/locale/locale.alias en_US.UTF-8
# RUN apt-get update && apt-get install -y locales && rm -rf /var/lib/apt/lists/* \
# 	&& localedef -i en_US -c -f UTF-8 -A /usr/share/locale/locale.alias en_US.UTF-8
# ENV LANG en_US.utf8

# RUN localedef -i en_US -c -f UTF-8 -A /usr/share/locale/locale.alias en_US.UTF-8
# ENV LANG en_US.utf8

WORKDIR /home/jovyan/work/lab
