# Doacker

Pure goodness! 🐳

Our internal set of utilities to manage Docker containers

## Installation

```sh
sudo curl -L https://github.com/lotrekagency/doacker/archive/master.tar.gz | tar xvfz - --strip 2 -C /usr/local/bin/
```

## Utilities

### Docker Stop All

This command stop all containers

```sh
docker-stopall
```

### Docker Remove All

This command removes all stopped containers

```sh
docker-removeall
```

### Docker Clean

This command stop and removes all containers

```sh
docker-clean
```

### Docker Db Dump

This command creates a database sql dump. Only PostgreSQL and MySQL supported.

```sh
docker-dbdump <container>
```

### Docker Db Restore

This command restores a database dump. Only PostgreSQL and MySQL supported.

```sh
docker-dbrestore <container> <sqldump>
```
