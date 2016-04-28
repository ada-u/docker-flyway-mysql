# Docker flyway and MySQL client

Flyway is database migration tool.

# About flyway

> Flyway is an open-source database migration tool. It strongly favors simplicity and convention over configuration.

[Flyway](https://flywaydb.org/)

# Install

# Usage

```
$ docker run -i -t uadachi/flyway-mysql flyway -url=jdbc:mysql://127.0.0.1/dbname -user=root -password=password migrate
```
