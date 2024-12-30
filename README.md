# SQLAlchemyTutorial

Running through the labs at https://github.com/auth0-blog/sqlalchemy-orm-tutorial/tree/master
actual tutorial at: https://auth0.com/blog/sqlalchemy-orm-tutorial-for-python-developers/

## PostgreSQL setup

```
# create a PostgreSQL instance
docker run --name sqlalchemy-orm-psql \
    -e POSTGRES_PASSWORD=pass \
    -e POSTGRES_USER=usr \
    -e POSTGRES_DB=sqlalchemy \
    -p 5432:5432 \
    -d postgres

# stop instance
docker stop sqlalchemy-orm-psql

# destroy instance
docker rm sqlalchemy-orm-psql
```

