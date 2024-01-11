## Start a postgres docker container 

```
docker run --name postgres12 -p 5432:5432 -e POSTGRES_USER=root -e POSTGRES_PASSWORD=secret -d postgres:12-alpine  
```

## Login to a postgres container
```
docker exec -it postgres12 psql -U root
```



