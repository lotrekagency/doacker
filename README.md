# Doacker 🍫

Pure goodness! 🐳Our internal set of utilities to manage Docker containers

## Installation

```sh
sudo curl -L https://github.com/lotrekagency/doacker/archive/master.tar.gz | tar xvfz - --strip 2 -C /usr/local/bin/
```

## 📦Manage containers

A set of utilities to manage containers.

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

## 🗃Dump and Restore databases

A set of utilities to dump and restore database, very useful during nightly backups.

⚠️ Only *PostgreSQL* and *MySQL* supported at the moment. 

Required env variables for *MySQL*

- MYSQL_DATABASE
- MYSQL_USER
- MYSQL_PASSWORD

Required env variables for *PostgreSQL*

- POSTGRES_USER
- POSTGRES_DB

### Docker Db Dump

This command creates a database sql dump.

```sh
docker-dbdump <container>
```

### Docker Db Restore

This command restores a database dump.

```sh
docker-dbrestore <container> <sqldump>
```
