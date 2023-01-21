## connect to container

```sh
docker-compose exec mongodb bash
```

## connect with mongosh

```sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
```

```sh
show dbs
show collections
```

```sh
use("test_store")
db.products.find()
```
