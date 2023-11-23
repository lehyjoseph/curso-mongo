## Connection to container bash

```sh
docker compose exec mongodb bash
```
```sh
show dbs
show collections
```
## Connect to mongosh
```sh
mongosh "mongodb://root:example@localhost:27017/?authMechanism=DEFAULT&tls=false"
```
