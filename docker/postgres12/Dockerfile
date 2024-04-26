FROM postgres:12.0

RUN apt-get update
RUN apt-get install -y postgresql-plpython3-12

COPY pgsmtp-0.1.1/ /usr/share/postgresql/12/extension/

RUN localedef -i en_US -c -f UTF-8 -A /usr/share/locale/locale.alias en_US.UTF-8
ENV LANG en_US.utf8