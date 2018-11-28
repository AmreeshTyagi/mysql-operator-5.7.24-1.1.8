FROM mysql/mysql-server:5.7.24-1.1.8

COPY bin/linux_amd64/mysql-agent /

USER mysql

ENTRYPOINT ["/mysql-agent"]
