# tbls basic demo

## install tbls

> for mac

```code
brew install k1LoW/tap/tbls
```

## running

* start pg server

```code
docker-compose up -d
```

* create  demo table

```code
CREATE TABLE userlogins (
    id SERIAL PRIMARY KEY,
    username text
);
```

* running tbls

```code
tlbs doc

````