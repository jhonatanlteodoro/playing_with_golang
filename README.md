# playing_with_golang
A repository to store my tests and sample project created using golang


### Run project
```bash
go run ./cmd/web
```

### Run Maria DB
```bash
docker run -d --name mariadb -e MARIADB_USER=user -e MARIADB_PASSWORD=my_cool_secret -e MARIADB_ROOT_PASSWORD=my-secret-pw  mariadb:alpine
```
