# Yannai's todo backend

### Configuring

Set environment variables

```sh
 DATABASE_URL = Postgre database connection url
 BACKUP_DATABASE_URL = (Optional) Mongo database connection url
 PORT = Server running port (default: 3000)
```

### Running

```sh
 npm i
 npm start
```

### Running with default postgresql config

```sh
DATABASE_URL='postgresql://postgres:password1@localhost/postgres' npm start
```
