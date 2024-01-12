FROM mysql:latest

COPY ./my.cnf /etc/my.cnf

ENV MYSQL_ROOT_PASSWORD=Admin@123
ENV MYSQL_DATABASE=userdata
ENV MYSQL_USER=a
ENV MYSQL_PASSWORD=Admin@123
CMD ["--default-authentication-plugin=mysql_native_password"]
