# https://github.com/Microsoft/mssql-docker
FROM mcr.microsoft.com/mssql/server:2019-CU10-ubuntu-20.04

USER root:root

COPY entrypoint.sh /

ENTRYPOINT ["/usr/bin/bash", "/entrypoint.sh"]