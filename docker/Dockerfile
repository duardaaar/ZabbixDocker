FROM zabbix/zabbix-server-mysql:ubuntu-7.0-latest

USER root
RUN apt-get update && \
    apt-get install -y odbc-mariadb unixodbc && \
    apt-get clean
USER zabbix
