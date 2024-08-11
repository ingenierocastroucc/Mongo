## Connect to container

```sh
docker-compose exec mongo db bash
```
## Connect with mongosh


```sh
mongosh ""
```

```sh
show dbs
show collection
```

```sh
use("CampusVirtual")
db.Matriculas.find()
```