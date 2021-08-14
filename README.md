# flask-sqlalchemy


## psycopg2 가 설치가 되지 않을때
```
$ brew install postgresql
$ pg_ctl -D /usr/local/var/postgres start
$ brew install openssl
```

## 작업시 에러 봉착

그리고 해결 책으로 blueprint 제시함
- [model circle import](https://stackoverflow.com/questions/22929839/circular-import-of-db-reference-using-flask-sqlalchemy-and-blueprints)



## Reference
- [realpython](https://realpython.com/flask-by-example-part-2-postgres-sqlalchemy-and-alembic/)
- [realworld](https://github.com/gothinkster/flask-realworld-example-app)
- [flask alembic example](https://realpython.com/flask-by-example-part-2-postgres-sqlalchemy-and-alembic/)