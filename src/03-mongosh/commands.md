## Connect to container

```sh
sudo docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh  "mongodb://<user>:<password>@localhost:27017/?tls=false&authMechanism=DEFAULT"
```
### or
```sh
mongosh  "mongodb+srv://<user>:<password>@cluster0.3j9uaso.mongodb.net/"
```

## Commands into connection
```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```