# How to install Nginx Proxy Manager

First rename the `.env.example` to `.env` and fill in your data there.

```env
#Proxy Settings
DB_MYSQL_HOST="db"
DB_MYSQL_PORT=3306
DB_MYSQL_USER="npm"
DB_MYSQL_PASSWORD="npm"
DB_MYSQL_NAME="npm"

#Database Settings
MYSQL_ROOT_PASSWORD="npm"
MYSQL_DATABASE="npm"
MYSQL_USER="npm"
MYSQL_PASSWORD="npm"
```

And copy the `docker-compose.yml` into the same directory.

then you can run `docker-compose up -d` and if you haven't changed the port settings go to `server-ip:81`.

There you have to login with the default login data first

```txt
email: admin@example.com
password: changeme
```

and then follow the steps of the Proxy Manager!